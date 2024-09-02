# Lab Assignment 2

In this lab, each student team will complete several tasks in _Packet Sniffing and Spoofing_ and _TCP/IP Attack_ lab modules using SEED Lab Ubuntu 20.04 VM. 

## Recommended background
Basic knowledge of computer networking is recommended. To get the most out of this lab, you might wish to work with someone who has experience in computer networking (e.g., TCP/IP, socket programming) and/or spend some time learning about it. Additionally, familiarity with Docker networking configurations is important, as the lab may involve setting up and troubleshooting network communication between Docker containers.

## Environment Setup

You need multiple docker containers for this lab. Additional instructions: docker documentation (https://docs.docker.com/) Pay special attention when you set up the networking of the docker containers.

## 1. Packet Sniffing and Spoofing (35 points)

https://seedsecuritylabs.org/Labs_20.04/Files/Sniffing_Spoofing/Sniffing_Spoofing.pdf

You only need to complete **Lab Task Set 1**, which includes four tasks: (1) Sniffing Packets, (2) Spoofing ICMP Packets, (3) Traceroute, and (4) Sniffing and then Spoofing.

**Sample code can be found here** (from the SEED Lab's creator): https://github.com/kevin-w-du/BookCode/tree/master/Sniffing_Spoofing

**Note:** When running the code for Task 1.3, please use your home network, as the school's network has security measures that may prevent the code from running successfully.

**Additional Question:** In 3.3 Task 1.3: Traceroute, we increment the TTL value to get the number of routers flowing through. Please explain why we can make this. (Hint: Getting to know what TTL is and the process of routing.)

## 2. TCP/IP Attack (15 points)

https://seedsecuritylabs.org/Labs_20.04/Files/TCP_Attacks/TCP_Attacks.pdf

You only need to complete Task1: SYNFlooding Attack (task 1.1 to task 1.3): **SYN Flooding Attack**.

**Additional Question:** Please explain how the SYN cookie mechanism can help to defend the SYN flood
attacks.

## Submission Details

- Each group only needs to submit one report in PDF format.
- Please list group members in your report explicitly.
- Only typed reports are accepted.

## Grading

- Completeness (30 points): All the steps as instructed in the lab manual must be included in the report with adequate evidence.
- Presentation (20 points): The report must be clear and correct in organization and writing with adequate explanation.
