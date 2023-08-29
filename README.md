# About

DFP is simple bash script to quickly setup docker php enviroment (apache or cli)

# Instalation

You can put dfp in any folder you want, just make it executable with command:

`sudo chmod u+x dfp`

If you want to keep dfp globally you need to put this file in one of linux global scripts folder (ex. /bin or /usr/local/bin)

Script should be runned with sudo becouse of docker commands used in.

# Usage

`dfp [start | stop | help] [cli | apache] php-version script.php`

### Starting example cli script

`dfp start cli 8.2 script.php`

### Starting example apache enviroment

`dfp start apache 7.4 test-project/`

### Stopping specific container

`dfp stop apache 7.4`

### Stopping all containers

`dfp stop`

# Preview

![Alt text](/test-project/apache.png?raw=true)
![Alt text](/test-project/cli.png?raw=true)