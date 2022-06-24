# Web Enumeration Tool

---

This is Web Enumeration Tool with GUI to automate tasks like

- port scanning
- Directory Bruteforce
- Find WayBack Urls
- Find SubDomains and other info

## About

---

This is a python tool designed to enumerate subdomains of websites using
the cert.sh and dnsdumpster.
</br>
The Port Scanning is done thorough
simple and basic technique in port scanning you give
inputs the range of port in 'from' and 'to' the range
of ports you want to look for, and you can also
decide the number of threads.
</br>
In Directory Bruteforce you select the wordlist from
given options and start attack.
</br>
For finding the WayBack Urls it's very simple you
just hit the button, and you are good to go.
</br>

## Installation

---

```
   git clone https://github.com/AnuragTaparia/bug_bounty_automation.git
```

### Recommended Python Version:

---

This Tool currently supports Python 3.

---

This project is located inside Directory "bug_bounty_automation"
change the Directory:

```
     cd bug_bounty_automation
```

## Dependencies:

---

This tool depends on the `beautifulsoup4, colorama, imutils, opencv_python, Pillow and requests` python modules.
</br></br>
These dependencies can be installed using the requirements file:

- Installation on Windows:

      pip install -r requirements.txt

- Installation on Linux:

      sudo pip install -r requirements.txt

## Run

---

Run the `Main_GUI.py` file:

- Windows:

```
       Python Main_GUI.py
```

- Linux:

```
       sudo python3 Main_GUI.py
```
