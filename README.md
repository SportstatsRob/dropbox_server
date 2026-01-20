# dropbox_server
Dropbox Server Scripts and Configuration

Requirements:

1. Download dropbox daemon (dropboxd)
3. Create /dropboxdata directory and set owner/permissions for ubuntu:
     drwxr-xr-x   5 ubuntu ubuntu  4096 Jan 20 19:20 dropboxdata
4. Create symlink for /home/ubuntu/Dropbox to /dropboxdata
5. Run setup to configure dropboxd to use sportstats timing account.
6. Download dropbox CLI based client  (dropbox)
7. Exclude everything and then add TimingUploads
     dropbox exclude add *
     dropbox exclude remove TimingUploads
8. Install contents from scripts into /home/ubuntu/scripts
9. Install contents from crontab.txt
