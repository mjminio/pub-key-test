# MinIO Public Key Repo

To add keys for your server, do the following.

1. Clone this repo
2. Add your PUBLIC ssh key to `/keys/YOURUSERNAME-keys`. Replace `YOURUSERNAME` with your actual username for logging in to the servers. One key per line. It must be in the `keys` dir and be named `YOURUSERNAME-keys`. 
3. Commit the change
4. Work with datacenter engineer to run Ansible script to update your key