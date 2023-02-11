# sysinfo
- Linux system analysis tool 

## Download
- Get latest version from [releases](https://github.com/cpy-dev/sysinfo/releases)

- Or just clone this repo

      $ git clone https://github.com/cpy-dev/sysinfo.git 

## Usage
- The tool requires Python3 to be installed
- CPU usage scanning requires sysstat package to be installed on the system
- Information can be displayed all at once, or separately by using arguments
  
      $ sysinfo


- Information and relative argument (arguments can be combined):

      usage: sysinfo [-h] [-ut] [-lu] [-ap] [-stu] [-stt] [-ip] [-ru] [-rt] [-su] [-st] [-cu] [-ct] [-sl] [-cs] [-hn] [-k] [-cr] [-csw] [--pretty]

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
		  -cr         Cached RAM
		  -csw        Cached Swap
		  --pretty    When combined with options, shows them with full description

	Execution with no argument will display all info
	More than one argument can be specified
	If some value cannot be retreived, it won't be shown

# Example
- Example run on BananaPi M64


		Local users: 2     Up time: 2:02	Current session: /dev/pts/0
		Kernel: 6.1.7-sunxi64		Usage of /: 14% of 58G
		Host name: m64		IP address: 10.7.0.1  192.168.1.32
		RAM usage: 17% of 1.94G	Cached RAM: 262M
		Swap usage: 0% of 994M	Cached Swap: 0M
		CPU usage: 3%			CPU temperature: 40°C
		Active processes: 151		System load: 5%
