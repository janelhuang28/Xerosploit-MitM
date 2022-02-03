# Xerosploit-MitM
Man in the Middle (MitM) attacks is where an attacker can intercept a request and alter it. This requests can be terminated or redirected (altered) back to the victim.

## Prerequisites

1. Download Xerosploit with ``git clone https://github.com/LionSec/xerosploit``
2. Install the require packages by ``cd xerosploit && sudo python install.py``
3. Install all dependencies by ``sudo apt install nmap hping3 build-essential ruby-dev libpcap-dev libgmp3-dev``
4. Install python dependencies ``sudo pip install -t /usr/lib/python2.7/dist-packages tabulate terminaltables`` (If pip3 not installed, install with ``sudo apt install python3-pip``
5. Run Xerosploit with ``xerosploit``

## Running the Attack

### Scan for Targets
1. Scan for targets by typing ``scan``
2. After selecting a target IP example: 192.168.1.144

## Shaking the Browser
1. Now we just want to shake the browser, so type ``move``
2. Type ``run`` to execute the command
![image](https://user-images.githubusercontent.com/39514108/152272440-5ef06da4-4d12-48a8-80a4-924f4e6df4fd.png)
This begins to shake the user's page. (Note that http must be used)
3. Type ``back`` to return back to the attack page
