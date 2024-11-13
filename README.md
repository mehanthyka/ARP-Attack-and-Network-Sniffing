# ARP-Attack-and-Network-Sniffing
# Explore Network Sniffing and ARP Attacks

# AIM:

To explore network sniffing and ARP Attacks

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:


### Step 3:
Open terminal and try execute some kali linux commands

## ARP Attacks:  
ARP spoofing: A hacker sends fake ARP packets that link an attacker's MAC address with an IP of a computer already on the LAN. 
Boot kali and Windows7 virtual machines.
In windows 7 give the command arp -a
## OUTPUT:
# ![image](https://github.com/Roselineb/ARP-Attack-and-Network-Sniffing/assets/128909895/5ade3192-293a-436d-942b-f785fa335cee)


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:

# ![image](https://github.com/Roselineb/ARP-Attack-and-Network-Sniffing/assets/128909895/b6105e25-f9a8-4d28-9464-c910b87049f0)

## dsniff:

In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
# ![image](https://github.com/Roselineb/ARP-Attack-and-Network-Sniffing/assets/128909895/c426f3cc-47e2-4631-aaae-ba1244ff9633)


In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
# ![image](https://github.com/Roselineb/ARP-Attack-and-Network-Sniffing/assets/128909895/8123604d-0355-4114-8e7c-52728d5d08ef)

Invoke the wireshark and examine the various menus  and controls of the tool:
# ![image](https://github.com/Roselineb/ARP-Attack-and-Network-Sniffing/assets/128909895/6e4f849a-9c76-4376-b777-0a9defbe64ba)


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
