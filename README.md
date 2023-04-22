# VoIP-Message-Tracking

## Network Shark

Network Shark is a software application that allows users to extract relevant information from VoIP packets between two end devices and decode the relevant data. The packets can be used to extract useful information like the IP addresses of the clients, the VoIP server, their location, their ISP details, time and date of communication, and duration of communication.


## Getting Started

1. Clone the repository: `git clone https://github.com/gifton-paul-immanuel/network-shark.git`
2. Install the required Python packages: `pip3 install -r requirements.txt`
3. Run the tool: `python3 software.py`

### Features

 Users can upload a VoIP packet with the case number. The software dynamically analyzes the packets using modules like pyshark after we upload the packet capture.The analyzed data would be presented in a PDF report format graphically and analytically readable. 

### Report Generation Pages

- TCP/UDP Report
- VoIP Packet Composition Report
- SIP/RTP Packet Data Report
- Duration of the Call Report

## Supported Platforms

This tool is only for Linux. However, it should work on any platform that supports Python3 by making some changes in the code and the required Python packages.

## Dependencies

- tkinter
- customtkinter
- PyPDF2
- pyshark
- matplotlib
- numpy
- fpdf
- os
- PIL

### Screen-Shots:

![[Pasted image 20230423021431.png]]

![[Pasted image 20230423021520.png]]

![[Pasted image 20230423021551.png]]

![[Pasted image 20230423021627.png]]
