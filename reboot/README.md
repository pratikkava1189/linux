This is playbook for rebooting the machine.

What does the playbook do?
1. Ask for confirmation if you want reboot the server.
2. After reboot, playbook will halt for 60 seconds.
3. ansible will try to ping & wait for the server until it returns.
4. Check the uptime after reboot.

Developed by Pratik Mansukhlal
