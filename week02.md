Day01
#Converting decimal to binary
13= 1101 
200=11001000
255=11111111

#Converting binary to decimal 
10101010=170
01100100=100
11000000=192

#The seconds 50MB file take to download at 10Mbps
40 seconds

#Speed test at fast.com and how long a 50MB would take on it 
speed on fast.com =430Kbps
Time for 50MB file to run= 930 seconds

Day02
#IPv4 Address = 192.168.21.244
Subnet Mask = 255.255.254.0
Default Gateway = 192.168.20.1

#Addresses in binary
192.168.1.1=11000000.10101000.00000001.00000001
192.168.21.244=11000000.10101000.00000001.

#Private Addresses
192.168.0.10
10.1.2.3
172.20.5.4

#Public Addresses
8.8.8.8.
172.32.0.1
41.66.10.20

#My ip on Google
102.223.92.112

#Why my ip on Google is different from my ipconfig one
My ip on Google is a public address assigned to my router and my ipconfig is my private address used only inside my local network.They are differnt because of NAT -my router translates my private address to the public address so i can access the internet

#Ping Server
ping 8.8.8.8
a. time= 42ms, TTL= 120
b. lost number= 1(25% loss)

ping google.com
a.time= 126ms, TTL= 110
b. lost number= 0(0% loss)

#Day03
a. nslookup google.com
IPv4= 192.168.1.1
IPv6= 2a00:1450:4009:c19::65

b. nslookup -type=mx gmail.com
mail server= gmail-smtp-in.l.google.com
small preference number= 5

#DNS memory
Record Name: wifiportal.ktu.edu.gh
A (Host) Record: 102.223.93.19
Time to live:15534

#The Host file
Number of lines that does not start with "#" is = 0

Why malware might add a line like 6.6.6.6 mtn.com.gh
So that when i type mtn.com.gh, my laptop goes to the hacker's fake server at 6.6.6.6 instead of the real MTN site so it can steal my details. 

#3 Lookalike names a scammer could register for mtn.com.gh and how to spot each.
a. rntn.com.gh-the first letter isn't m buh rather r + n
b. mtn-com-gh.com- Real site ends in .com.gh.This just ends with just .com and uses dashes.
c.mtnn.com.gh- real mtn has one "n" and this has two "n".




