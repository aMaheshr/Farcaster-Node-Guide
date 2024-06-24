
# Farcaster Hubble Node Setup Guide

![far](https://github.com/aMaheshr/Farcaster-Node-Guide/assets/113323750/2ee82734-237f-4020-b81f-b230bf90c1d3)



## Lets Start
## Requirements :

### STEP 1

-- For Better node performance, select a Highend VPS with a high-frequency CPU and RAM.

- 16 GB RAM
- 4 CPU cores or vCPUs
- 40 GB of free space

### STEP 2

- Register on Warpcast - ( Require $5 Setup fees )
 -- Link to Register : https://warpcast.com/~/invite-page/673854?id=c9d6bf41

- Navigate to your profile, select About, and note down your FID

  ![id](https://github.com/aMaheshr/Farcaster-Node-Guide/assets/113323750/6d5251bc-d9cc-464a-939d-b81a669bd74b)



### STEP 3
- Create RPC ENDPOINTS using INFURA - https://app.infura.io
-  choose Ethereum & Optimism ENDPOINTS

  ![rpc](https://github.com/aMaheshr/Farcaster-Node-Guide/assets/113323750/45c3da86-2d30-4ba4-8e6f-5a5112f6a78d)



## Lets install Farcaster Hubble NODE :

- Login ur IP using Putty OR Termius Software

- just copy and paste Below CMDs in ur Terminal


#### #Install Screen
~~~bash
sudo apt update -y
sudo apt install screen -y
screen -S Hubble
~~~
Remember Screen name : Hubble

#### #Farcaster Installation Script

~~~bash
curl -sSL https://download.thehubble.xyz/bootstrap.sh | bash
~~~

- its takes 5 mins to Installing Script

- After Script Succesfully installed

- just copy & paste RPC ENDPOINTS one by one
    - Ethereum RPC
    - Optimism RPC
    - Farcaster FID

- #### Now node start Running & Start Syncing

  ![node](https://github.com/aMaheshr/Farcaster-Node-Guide/assets/113323750/c9e0632d-0d73-4812-a3eb-07a4ecf8c3e1)


- u must Deattach ur Screen : #Press CTRL + A + D

#### Re-Enter ur Node Screen-Execute the below CMD

~~~bash
screen -r Hubble
~~~

- #### Access ur Farcaster Dashboard : http://your_VPS_iP:3000

  ![dash](https://github.com/aMaheshr/Farcaster-Node-Guide/assets/113323750/20f70ab4-792d-4e31-9f04-44a3da65cc77)



### Additional

#### if ur Node Stop Working use Below CMD

~~~bash
cd ~/hubble && ./hubble.sh upgrade
~~~

#### Thats it🧑‍💻

DISCLAIMER : *DYOR* There is no Guarantees Rewards or Future Airdrops :  This are all Speculations.Please consider carefully before participating.
