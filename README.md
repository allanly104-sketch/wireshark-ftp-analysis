# wireshark-ftp-analysis
A VirtualBox networking lab analyzing FTP traffic between Windows 10 and Kali Linux using Wireshark.
# FTP Traffic Analysis with Wireshark

## What I Learned

- How Host-Only networking works
- How to test connectivity using ping
- How FTP uses TCP port 21
- How to configure an FTP server on Linux
- How to capture FTP traffic using Wireshark
- Why FTP is insecure because credentials are transmitted without encryption
<img width="941" height="852" alt="Windows-ping" src="https://github.com/user-attachments/assets/4abb325a-8f0c-4bd1-b1eb-3cfaf0da11bc" />
### FTP Connection Test

Successfully connected from the Windows 10 VM to the FTP server running on Kali Linux and retrieved a directory listing.
<img width="551" height="423" alt="FTP-successful-login" src="https://github.com/user-attachments/assets/a2259eb1-e5d7-4eb3-9ff8-c132fcf2feb0" />
I connected from the Windows 10 VM to the FTP server running on Kali Linux. I was able to authenticate and retrieve a directory listing.
<img width="1220" height="312" alt="Wireshark-FTP-capture" src="https://github.com/user-attachments/assets/03a051eb-0227-4991-9812-b790a10c7053" />
I captured the FTP session using Wireshark. The capture showed FTP commands such as USER and PASS being transmitted without encryption. The password shown in the capture was redacted before publishing the screenshot.
