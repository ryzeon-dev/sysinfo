# sysinfo
- Linux system analysis tool 

## Download
- Just clone this repo

      $ git clone https://github.com/cpy-dev/sysinfo.git 

## Usage
- The tool requires Python3 to be installed
- CPU usage scanning requires sysstat package to be installed on the system
- Information can be displayed all at once, or separately by using arguments
  
      $ sysinfo


- Information and relative argument (arguments can be combined):

      usage: sysinfo [-h] [-ut] [-lu] [-ap] [-stu] [-stt] [-ip] [-ru] [-rt] [-su] [-st] [-cu] [-ct] [-sl] [-cs] [-hn] [-k]
      
      Linux system analysis tool
      
      options:
        -h, --help  show this help message and exit
        -ut         Up time
        -lu         Local users
        -ap         Active processes
        -stu        Storage usage
        -stt        Total storage
        -ip         IP address
        -ru         RAM usage
        -rt         Total RAM
        -su         Swap usage
        -st         Total swap
        -cu         CPU usage
        -ct         CPU temperature
        -sl         System load
        -cs         Current session
        -hn         Host name
        -k          Kernel
      
      Execution with no argument will display all info
      More than one argument can be specified
      If some value cannot be retreived, it won't be shown
