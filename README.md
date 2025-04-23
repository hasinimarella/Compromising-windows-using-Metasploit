# Compromising-windows-using-Metasploit
Compromising windows using Metasploit
# Metasploit
Compromising windows using Metasploit

# AIM:

To Compromise windows using Metasploit .

## DESIGN STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:

Open terminal and try execute some kali linux commands

## EXECUTION STEPS AND ITS OUTPUT:


1. Find the attackers ip address using ifconfig:
## OUTPUT:
![alt text](ifconfig.png)

2. Generate Payload Using msfvenom:

Execute the following command to generate a Windows Meterpreter reverse shell payload.exe 
## OUTPUT:

![alt text](image.png)

## step3.Invoke msfconsole:

![alt text](image-1.png)

![alt text](image-2.png)

## step 4.SetUp an HTTP Server:

![alt text](<exp 6.5.png>)

## Step5:Distribute the Payload:

![alt text](<exp 6.4.png>)

## Step6: Establish a Connection:
![alt text](exp6.3.png)

## Step7:List Commands:
![alt text](image-3.png)

## Step8:

![alt text](image-4.png)
## RESULT:
The Metasploit framework is  used to compromise windows and is examined successfully.
