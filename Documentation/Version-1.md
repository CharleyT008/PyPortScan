# Version 1 - Basic Port Scanner

## Overview
This version of the port scanner was about establishing the basics to understand the basics and provide me a baseline to improve later on. I used Python's
built in socket library for IP address handling. the program scanned all 65,535 ports on a target, which worked. However, it was too slow. This is because the
program seemed to wait for a connection timeout until moving onto the next port


## Technologies Used
- Python
- Socket library
- IP networking

## What went well
- The program scanned ports and outputted open ones
- The program handled IP host names and validated IP addresses

## Issues to improve
- One port was scanned at a time which took too long


## Screenshots
<img width="1442" height="112" alt="image" src="https://github.com/user-attachments/assets/0d255da2-d7ad-4c91-aa6b-88c0acf2471c" />
