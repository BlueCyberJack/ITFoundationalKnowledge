# IT Foundational Knowledge
This part of my portfolio will show evidence of my journey to learn the basic knowledge and skills within IT. 
The objective is to build a foundational knowledge that I can apply to cybersecurity learning. 


### Operating System Foundations

[Coursera - Operating System Foundations.pdf](https://github.com/user-attachments/files/19524770/Coursera.-.Operating.System.Foundations.pdf)

Module 1 - This module was very much about easing the student into learning about operating systems (OS) by explaining what an OS actually is and some common misconceptions. It provided a brief overview of the different OS available starting with the most common being Windows and then showed MacOS and Linux.

Module 2 - The Windows command line was introduced which showed the very basic commands and useful shortcuts to use the command line efficiently. I copied the commands being shown on my own computer which was good to get 'hands-on' even if it was an extremely brief introduction to using commands. 

Module 3 - This next module focused on using the Linux OS and its command shell via the course provider's website. I don't use and never have used Linux as an OS so this module was really useful. I did access a virtual Linux terminal via the course provider's website but unfortunately I couldn't find the specific lab to follow the commands step-by-step. 
Nevertheless, it was good to get some hands-on experience with using Linux, even if it only involved the most basic of commands. This module has made me realise that I need to get some experience using Linux and along my journey I plan on completing a course that focuses on Linux and using its command shell.

Module 4 - This was not a practical module but was very informative and beneficial. Keatron Evans (course teacher) showed a real-time pentetration test. It covered the five phases of completing the 'pentest' and also emphasised how most of the work involved was not what you would regard as 'hacking' but actually basic command line skills and knowledge. 




### Introduction to Networking 


[Coursera - Introduction to Networking.pdf](https://github.com/user-attachments/files/19525034/Coursera.-.Introduction.to.Networking.pdf)

This was a short course with only 1 learning module that covered the OSI model, TCP/UDP, IP protocol, ethernet fundamentals, sending data and data centre designs. The course itself was a good starting point in learning about networks but being someone with almost no IT knowledge, I did find it difficult to fully grasp the learning being delivered. Lots of new information was thrown at me and at times it was hard to digest and understand some of the concepts to a level where I felt confident in my understanding. However, I feel this is natural in that, how can someone become confident in something completely new after less than an hour of studying. After the course, I felt like I had become introduced to the basics of networking and knew about the basics but not at a level where I'd be confident in talking about it in depth. Therefore, I jumped straight into another course about networks which really cemented my understanding. 


### Computer Networks and Network Security

[Coursera - Computer Networks and Network Security.pdf](https://github.com/user-attachments/files/19525081/Coursera.-.Computer.Networks.and.Network.Security.pdf)

Module 1 - Started by introducing the hardware involved in networks and went on to explain about models, standards, protocols and ports. Similar to the previous course, there was lots of information to absorb but it was supported by offering practical sessions via labs to put the theory into practice. I really enjoy this style of teaching as I personally find that it helps with understanding new concepts if I get 'hands-on' experience. Most of this module's content was things that I'd already covered in the previous course which was brilliant in that I became confident in my understanding going on to the second module.

Module 2 - This module focused heavily on IP addresses and then went on to cover the basics of routing and switching within networks. Again, it utilised virtual lab sessions to provide the opportunity to get some practical experience with the theory being delivered. I learnt how an IP address is made up of four octets, holds both a numerical and binary value, and how you can manually convert IP addresses to its other value using a mathematics formula. To support my learning I visited other websites such as 'networkacademy.io' where the concept was explained futher. I then completed a practical lab session where I had to determine the subnet mask of an IPv4 address using a subnet calculator website and the same for IPv6 addresses using host calculation. The second part of the module covered routers and swtiches. It covered ARP, NIC, MAC addresses and layer 2 & 3 of routing. I learnt how important ARP is for transmitting data accurately across networks and how routing tables make that process efficiently as possible. 

Module 3 - I learnt about network protocols and security measures by combining theoritcal learning with practical lab sessions. It started by explaining TCP and UDP when sending data and provided real-life examples of when each would be used, e.g. TCP for emails and UDP for live-streaming. Alot of the learning I had already covered, but again, it was really good to revisit how TCP and UDP works to fill in my knowledge gaps and to really cement that the key fundamentals. After learning the theory it was time to put it into practice by using Wireshark. I'd never used Wireshark before but I managed to follow the lab session guide and could see the difference in TCP and UDP data packets. However, Wireshark is definitely a tool that I plan on getting more experience with. The next part of the module explained the 'Application' layer. It covered DNS, DHCP, DNS filtering, syslog, network flows and user behaviour analysis (UBA). I recognised that this was now starting to touch upon some very basic cybersecurity methods such as DNS filtering to restrict access to malicious webistes and UBA to detect any breaches and it even spoke of being integrated into SIEM systems. 

Module 4 - This was the last learning module and the first half covered firewalls, Intrusion Detection System (IDS), & Intrustion Prevention System (IPS) and the differences between the three tools. I learnt that firewalls use stateless or stateful inspection to inspect data packets. Stateful inspections log data and inspect data packets more thoroughly whereas stateless completes a basic inspection of packets based on pre-defined rules. I then learnt about using firewall filters and ports which was used in the next lab session where I configured a firewall to block HTTP traffic by blocking port 80. Again, it was really useful being able to apply the theory to a real-life scenario via a virtual lab. The module then went on to cover IDS and IPS along with their key differences and pros & cons. The conclusion was that each type of cybersecurity has its limitations and negative points, so it is important to use a multi-layered approach to ensure that defences are as strong as possible against cyber attacks. Other tools such as NAT, NAC and EDR were covered which again shows that there are many tools available and that should be utilised to ensure strong cybersecurity defences.  

Module 5 - This module was about putting all of my new skills and knowledge into practice by completing a project that evidenced the learning over the four modules:

1. Design a network with subnets - this involved applying knowledge of network hardware and designs into designing my own network with subnets:
  
 [Task 1_network diagram.pdf](https://github.com/user-attachments/files/19525761/Task.1_network.diagram.pdf)


2. Calculate subnet addresses and subnet masks - I provided evidence that I understand how to calculate subnet addresses and subnet masks by creating a table:
   
  
[Task 2 table.docx](https://github.com/user-attachments/files/19525815/Task.2.table.docx)


3. Analyze HTTP/HTTPS Traffic for one website using Wireshark - I used Wireshark to analyse data packet. I successfully ran the analysis but it wasn't as concise as I would have liked, you can see port 443 in use which shows that I captured the HTTPS traffic but it hasn't filtered it as effective as I wanted and at the time I'm not sure what actions I did that prevented this or anything that I could do to improve the use of Wireshark. However, it did highlight a knowledge/skill gap which I plan on addressing by using Wireshark more and researching some tutorials etc.

  [Task3 - word image.docx](https://github.com/user-attachments/files/19525812/Task3.-.word.image.docx)

    

4. Configure firewall rules using Microsoft Windows Defender  Firewall - I followed the instructions on this task and was successful in making the changes to the firewall. However, on the very last part of the task I could still access the webiste that should have been blocked. I revisited the learning and followed the instructions a further three times from the start but kept getting the same result. This is something that I plan on revisiting and plan on finding an alternative lab session or project involving firewalls. 
   

[Task 4 screenshot 1.docx](https://github.com/user-attachments/files/19525791/Task.4.screenshot.1.docx)

[Task 4 screenshot 2.docx](https://github.com/user-attachments/files/19525792/Task.4.screenshot.2.docx)

[Task 4 screenshot 3.docx](https://github.com/user-attachments/files/19525793/Task.4.screenshot.3.docx)

[Task 4 screenshot 4.docx](https://github.com/user-attachments/files/19525801/Task.4.screenshot.4.docx)

[Task 4 screenshot 5.docx](https://github.com/user-attachments/files/19525802/Task.4.screenshot.5.docx)

[Task 4 screenshot 6.docx](https://github.com/user-attachments/files/19525803/Task.4.screenshot.6.docx)







