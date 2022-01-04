1. Implement firewall using iptables. Make sure that your configuration persists through reboot or unexpected shutdowns. Deny all incoming traffic outside of SSH. Make sure that your config works.
2. Make sure that users cannot login directly to root.
3. Install PostgreSQL, create a postgre user and database
4. Research how to create your own service to start/stop/restart an app.

### 1. Implement firewall using iptables. Make sure that your configuration persists through reboot or unexpected shutdowns. Deny all incoming traffic outside of SSH. Make sure that your config works.<br>

1.1 Configured Ansible Control node and one Ansible host using the [guide](https://github.com/Catchron/catchron-kb/blob/main/Ansible/Ansible%20Instance%20Prep.md#virtualbox-with-ubuntu-18046-lts) I created.

1.2
