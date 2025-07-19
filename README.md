# SniffUSB-USB-Surveillance-and-Alerting-Tool-for-Unauthorized-Device-Detection
"A real-time USB monitoring and alert system with screenshot-based evidence and email-based permission control."
In many secure environments, unauthorized USB device usage can lead to data theft or malware injection. This project aims to detect USB device insertions in real-time and send an email alert to the admin requesting permission to allow or deny access. The system runs on Kali Linux and uses Python, udev rules, and Gmail SMTP.
Purpose:
To detect unauthorized USB device connections on a Linux machine (like Kali) and instantly send an email alert with details, so that a system admin can allow or deny access. This helps protect from USB-based malware or data theft.
So, my main intension is to:
Whenever a USB device is inserted into your Kali Linux system, the script captures its details and immediately sends you an email asking for permission.
Now I’m installing required tool
Mailutils 
mailutils is a package in Linux used for sending emails directly from the terminal or shell scripts. It provides the mail command, which allows you to send simple text-based emails to local or external email addresses.

