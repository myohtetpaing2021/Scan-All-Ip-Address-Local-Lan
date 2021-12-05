# Scan-All-Ip-Address-Local-Lan
I will show you how to scan your local IP address using command cmd. you will never wast your time to manage your local address. -run command to scan and save it on the text file


cd desktop
dir
for /L %i in (0,1,255) do ping -n 1 -w 25- 192.168.2.%i>>ip-list.txt
