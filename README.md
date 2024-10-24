# HTB Initilisation script
This is used for automating the recon phase of most hackthebox web based boxes, seeing as most times I will start with nmap, subdomain scanning and directory enumeration. Why not use bash to just speed this up.

Sudo perms are required if you want this to add the ip/domain combo to the hosts file.

You may also need to change the location of the wordlists as this is configured to my subdomains wordlists I have saved.

## Usage
` ./recon.sh <IP> <DOMAIN> <DIRECTORY_NAME>`

- IP: HTB ip for machine
- DOMAIN: The domain name if applicable
- DIRECTORY_NAME: User choice to set up directory

## Requirements
- Tmux
- Nvim

### Credits
Thanks to [ev1lm0rty](https://github.com/ev1lm0rty/HTB-Recon) for the idea
