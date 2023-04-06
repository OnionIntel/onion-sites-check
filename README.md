
Name: Python Script for Checking Onion Sites over Tor

"""
This script checks a list of onion sites to see if they are running over Tor, and prints out their title and server version if they are.

The script first starts a local Tor process and configures a session to use Tor for requests. It then reads a list of onion sites from a file, loops through the sites and checks their status. If a site is running, it extracts its title and server version from the response and prints them out. If a site is not running, it prints out a message saying so.

Dependencies:
- stem
- requests
- BeautifulSoup

Usage: python onion2.py

Note: onion_sites.txt should contain a list of onion site URLs, with one URL per line.

Tested on:

DISTRIB_ID=Ubuntu
DISTRIB_RELEASE=22.04
DISTRIB_CODENAME=jammy
DISTRIB_DESCRIPTION="Ubuntu 22.04.2 LTS"

Build with openAI Chat GPT
