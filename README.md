# Introducing
This source code made for simple port scanner that written with python3

## 🐛 Purpose 
This tools for learn and understand the basic some Python libraries and Networking concepts. So, contribution very welcome😊

## 🌚 How to Use
``` bash
# HELP
main.py -h
usage: main.py [h] [-i IP | -d DOMAIN] [-p [PORT [PORT ...]]]  [-t THREAD]

# Optional Argue
  -h, --help                    =>  show this help message and exit
  -i IP, --ip IP                =>  Target's ip
  -d DOMAIN, --domain           =>  DOMAIN
                                    Target's domain name
  -p [PORT [PORT ...]], --port  =>  [PORT [PORT ...]]
                                    Target ports' number interval
  -t THREAD, --thread           =>  THREAD
                                    How many threads do you want to use?

# Example
main.py -d scanme.nmap.org -p 1 25 -t 4
[+] Port--> 22

main.py -i 127.0.0.1 -p 1 1000 -t 4
[+] Port--> 443
[+] Port--> 631
[+] Port--> 902

```