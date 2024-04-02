## 1. Connect to remote host via SSH
### ssh: 
This command is used to securely connect to a remote Linux server or machine over a network.

```
ssh username@remote_host
```


## 2. Transfer file from local directory to remote host.
### scp: 
This command is used to securely copy files and directories between local and remote systems or between two remote systems.

```
scp /path/to/local/file username@remote_host:/path/to/remote/directory
```
For example, to transfer example.txt from your local directory to a remote server:

```
scp /home/user/Documents/example.txt user@123.456.789.0:/home/user/remote_directory/
```
