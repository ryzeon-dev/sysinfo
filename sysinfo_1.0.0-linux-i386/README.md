# sysinfo
- Linux system analysis tool 

## Usage
- Information can be displayed all at once, or separately by using arguments
  
      $ sysinfo


- Information and relative argument (arguments can be combined):

      usage: sysinfo [-h] [-ut] [-lu] [-ap] [-stu] [-stt] [-ip] [-ru] [-rt] [-su] [-st] [-cu] [-ct] [-sl]
      
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

      Execution with no argument will display all info
      If some value cannot be retreived, it won't be shown