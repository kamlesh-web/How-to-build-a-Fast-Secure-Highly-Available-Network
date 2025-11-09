1. High Availability
-Reduced network downtime by 99.9% using HSRP.
-Increased avilabilty by creating redundant links and configured Rapid PVST+ to counter layer 2 loops.
-Increased avilability by configuring loopback interfaces.

2. Network Hardening/Security
-Boosted network security by configuring ACLs which allowed and denied packets based on set rules. 
-Increased device security by limiting acces through an MD5 password encryption.
-Increased network security by disabling unused ports which denied access to the network from rogue devices.
-Configured VLANs to logically seperate hosts on the network, it also ensured exposed subnets were contained and could not spread.
-Only allowed specific VLANs on each trunk ports to deny acces to traffic not in the specified VLANs.
-Monitored the network for security threats by filtering packets using open source tools like Wireshark.

3. Fast Network
-Configured etherchannels which helped increase bandwidth by combining multiple links into one logical link. 
-Utilised high speed links in the network such as Gigabit Ethernet and Fiber Optic cables which provided faster speeds.
-Ensured OSPF chose the best and fastest paths by configured an auto-reference bandwidth of 100000 different from the default reference bandwidth of 100.
-Increased speed on Serial Interfaces by configuring faster clock rates of 2000000 Hz.
-Enabled portfast on interfaces connected to end users to give users a fast experience especially after a switch boot up.

4. Scalability
-Configured Dynamic Routes using OSPF so routers could easily share databases and learn routes of newly added devices in the network automatically.
-Utilised Cisco 4331's 'Pay As You Grow' feature which allowed for upgrades without changing equipment.
-Documented a logical network topology of every networking equipment, their models, interfaces, link interfaces, end devices attached etc so tracking legacy or non functioning devices could be easier to schedule replacements.
