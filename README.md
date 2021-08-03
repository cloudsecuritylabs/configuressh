# configuressh

```
sudo apt update
sudo apt install openssh-server
sudo systemctl status ssh
sudo ufw allow ssh
```


```
SCP examples
remote host to local host:
$ scp username@from_host:file.txt /local/directory/
 

local host to a remote host:
$ scp file.txt username@to_host:/remote/directory/
 

directory from a remote host to local host:
$ scp -r username@from_host:/remote/directory/  /local/directory/
 

directory from local host to a remote host:
$ scp -r /local/directory/ username@to_host:/remote/directory/
 

```
