# MS17-010_MasiveScanner

Massive Scanner with Excel File for Vulnerability MS17-010

You Need Python 2.7.13 & install xlrd library. For install it run pip install xlrd

To scan a single server, use the script created by nixawk as follows:

Example:

$ python2.7 smb_exploit.py 192.168.206.152
[+] [192.168.206.152] is likely VULNERABLE to MS17-010! (Windows 7 Ultimate 7600)

To do so with a list of servers, fill the excel Windows_Lista.xlsx. It must contain the TCP / IP addresses of the Windows Servers.

Example:

python scan_smb_exploit.py 






