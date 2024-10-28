### Date:
# Ex-4: ARP-Attack-and-Network-Sniffing
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
## ARP spoofing: 
A hacker sends fake ARP packets that link an attacker's MAC address with an IP of a computer already on the LAN. 
Boot kali and Windows7 virtual machines.
In windows 7 give the command arp -a
## OUTPUT:


![1)](https://github.com/user-attachments/assets/352b462c-52d6-4a87-b598-e77f2993b1bc)
</br>
From kali linux issue the command :
```
sudo arpspoof -i eth0 -t <target system> <gateway>
```
## Output:

![2)](https://github.com/user-attachments/assets/e23eab51-0350-43cc-ad39-35377c48b8fe)

## dsniff:
In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org

## Output:

In Kali issue the following commands:
```
sudo dsniff
```
![3)](https://github.com/user-attachments/assets/5ff9173c-31a1-4f33-8d64-36fe4e8d6cbb)

## Output:

![4)](https://github.com/user-attachments/assets/762b23c4-d805-46c2-94a1-477d739d11f8)


## Wireshark:
Invoke the wireshark and examine the various menus  and controls of the tool:
## Output:
![5)](https://github.com/user-attachments/assets/8de52d49-3015-4ec6-afc3-a4fd0c217e0d)

## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
