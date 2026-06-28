Day 04 - Script Execution Permissions

Today I learned how to make a Linux script executable.

In Linux, every file has permissions. A script needs execute (x) permission before it can be run. Without execute permission, the script cannot be executed even if it exists.

In DevOps, scripts are used for automating tasks like application deployment, server setup, backups, monitoring, and maintenance. Giving the correct execute permission ensures these automation scripts run successfully.

Commands Used

ssh tony@stapp01
sudo su -
chmod 755 /tmp/xfusioncorp.sh
ls -l /tmp/xfusioncorp.sh

What I Learned

- "chmod" is used to change file permissions.
- "755" sets the permissions to "rwxr-xr-x".
- "ls -l" displays file permissions.
- Scripts require execute permission to run.
- File permissions are important for Linux security and automation.

Lab Status

✅ Successfully granted execute permission to the script and verified the changes.
