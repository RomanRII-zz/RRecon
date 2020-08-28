##############################################################################
##                                                                          ##
##    ▄████████    ▄████████    ▄████████  ▄████████  ▄██████▄  ███▄▄▄▄     ##
##   ███    ███   ███    ███   ███    ███ ███    ███ ███    ███ ███▀▀▀██▄   ##
##   ███    ███   ███    ███   ███    █▀  ███    █▀  ███    ███ ███   ███   ##
##  ▄███▄▄▄▄██▀  ▄███▄▄▄▄██▀  ▄███▄▄▄     ███        ███    ███ ███   ███   ##
## ▀▀███▀▀▀▀▀   ▀▀███▀▀▀▀▀   ▀▀███▀▀▀     ███        ███    ███ ███   ███   ##
## ▀███████████ ▀███████████   ███    █▄  ███    █▄  ███    ███ ███   ███   ##
##   ███    ███   ███    ███   ███    ███ ███    ███ ███    ███ ███   ███   ##
##   ███    ███   ███    ███   ██████████ ████████▀   ▀██████▀   ▀█   █▀    ##
##   ███    ███   ███    ███                                                ##
##                                                                          ##
##############################################################################

Prerequisites:
        Run installer.sh or manually install dependancies. (See Needed Software)

Tool Usage:
            ./RRecon.sh domain 'Company Name'
        EX: ./RRecon.sh google.com 'Google'
        EX: ./RRecon.sh capitalone.com 'Capital One'


Needed Software:
________________________________________________________________________________________________________________________________
| amass                  ||          Install location:'/home/*/go/bin/amass'                                                    |
| crawler                ||          Install location:'python3 /home/*/Tools/crawler/crawler.py'                                |
| eyewitness             ||          Install location:'python3 /home/*/Tools/EyeWitness/Python/EyeWitness.py'                   |
| ffuf                   ||          Install location:'/home/*/go/bin/ffuf'                                                     |
| findomain              ||          Install location:'/home/*/Tools/Recon-OSINT-Discovery/findomain/findomain-linux'           |
| github-subdomains      ||          Install location:'/home/*/Tools/github-search/github-subdomains.py'                        |
| hakrawler              ||          Install location:'/home/*/go/bin/hakrawler'                                                |
| httprobe               ||          Install location:'/home/*/go/bin/httprobe'                                                 |
| masscan                ||          Install location:'/home/*/Tools/Scanners/masscan/bin/masscan'                              |
| massdns                ||          Install location:'/home/*/Tools/massdns/bin/massdns'                                       |
| meg                    ||          Install location:'/home/*/go/bin/meg'                                                      |
| spiderfoot             ||          Install location:'python3 /home/*/Tools/Recon-OSINT-Discovery/spiderfoot-3.1/sf.py'        |
| sqlmap                 ||          Install location:'python3 /home/*/Tools/Exploitation/sqlmap-dev/sqlmap.py'                 |
| subjack                ||          Install location:'/home/*/go/bin/subjack'                                                  |
| sublister              ||          Install location:'python3 /home/*/Tools/Recon-OSINT-Discovery/Sublist3r/sublist3r.py'      |
| waybackmachine         ||          Install location:'python3 /home/*/Tools/waybackMachine/waybackMachine.py'                  |
| waybackurls            ||          Install location:'/home/*/go/bin/waybackurls'                                              |
________________________________________________________________________________________________________________________________|

________________________________________________________________________________________________________________________________
| amass                  ||          https://github.com/OWASP/Amass                                                             |
| crawler                ||          https://github.com/ghostlulzhacks/crawler                                                  |
| eyewitness             ||          https://github.com/FortyNorthSecurity/EyeWitness                                           |
| ffuf                   ||          https://github.com/ffuf/ffuf                                                               |
| findomain              ||          https://github.com/Edu4rdSHL/findomain                                                     |
| github-subdomains      ||          https://github.com/gwen001/github-search/                                                  |
| hakrawler              ||          https://github.com/hakluke/hakrawler                                                       |
| httprobe               ||          https://github.com/tomnomnom/httprobe                                                      |
| masscan                ||          https://github.com/robertdavidgraham/masscan                                               |
| massdns                ||          https://github.com/blechschmidt/massdns                                                    |
| meg                    ||          https://github.com/tomnomnom/meg                                                           |
| spiderfoot             ||          https://github.com/smicallef/spiderfoot                                                    |
| sqlmap                 ||          https://github.com/sqlmapproject/sqlmap                                                    |
| subjack                ||          https://github.com/haccer/subjack                                                          |
| sublister              ||          https://github.com/aboul3la/Sublist3r                                                      |   
| waybackmachine         ||          https://github.com/ghostlulzhacks/waybackMachine                                           |
| waybackurls            ||          https://github.com/tomnomnom/waybackurls                                                   |
________________________________________________________________________________________________________________________________|