# README #

```
sudo apt -y update
sudo apt-get install ssh ansible git aptitude wget unzip
wget https://github.com/skarlsson/ubuntu20_workstation/archive/master.zip
unzip master.zip
cd ubuntu20_workstation-master
```

```
ansible-playbook -i "localhost," -c local initial-ubuntu20.yml --ask-become-pass 
```

###### if you nned cuda a reboot is nessesary to load the new driver
```
nvidia-smi 
Fri Dec 25 16:49:12 2015
+------------------------------------------------------+
| NVIDIA-SMI 352.63     Driver Version: 352.63         |
|-------------------------------+----------------------+
```


