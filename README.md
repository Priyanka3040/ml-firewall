This is only applicable for Kali Linux
--Basic steps to setup this project in your Linux--

Commands to run 

1.
To install this repository,you have to run command in terminal
= sudo git clone...

2.
Unzip the file using below command
= unzip "filename"     (no need to put inverted commas)
= cd ML-firewall-main
= chmod +x *
= pip3 install libraries and requirements
= ./config.sh                   #This is where all the configurations of files will be setup.
After this,to run the webpage use the below given command
= service2 apache start
Then, you have to run python3 firewall.py and for all this you have to be the root superuser.
Command for this is:
= python3 firewall.py
