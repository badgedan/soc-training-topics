# WE INNOVATE - SOC TOPICS 
This is going to be a very high-level overview of the topics that were covered throughout the 5 weeks of **WE INNOVATE's SOC** training, obviously this is going to be my personal experience and curiosity so nothing here is a copy-paste process from the slides but just a student's understanding and note-taking.


Mainly the training was divided into  3 main technical parts
- **Introduction to Cybersecurity**
- **SOC Analysis**
- **SOC Engineering**

## Introduction to Cybersecurity
We've briefly discussed an overview for the **Operating Systems** and I recommend reading [**Operating Systems: Three Easy Pieces**](https://pages.cs.wisc.edu/~remzi/OSTEP/) as a source if you are interested in learning more about operating systems, after that we've done some history check on **Linux** and Architecture overview, I recommend checking out **[Linux Journey](https://linuxjourney.com/)** and TryHackMe's **[Linux Fundamentals Module](https://tryhackme.com/module/linux-fundamentals)**, TCM Security's **[Linux 101](https://academy.tcm-sec.com/p/linux-101)**, also we've applied those skills on **[OverTheWire's Bandit](https://overthewire.org/wargames/bandit/)**. 

Also you can expand your research on Linux's Firewall how they work, Syslogs, and Networking in Linux.

Continuing, with the operating systems, we've discussed the **Windows Active Directory**, you can check out TryHackMe's **[Active Directory Basics](https://tryhackme.com/r/room/winadbasics)** Room also check out this **[Reddit post](https://www.reddit.com/r/CompTIA/comments/11kij7k/recommendations_on_learning_active_directory/)**.


Going on to the **Network Security** topic, this is going to be mainly your own research but these are the topics that were covered
- **Firewalls, IDS, and IPS**
- **VPNs**
- **Antiviruses and EDRs, etc**

You can apply some rules on each topic of these such as to configure a set of rules on an IDS/IPS such as **[Snort](https://www.snort.org/)**, you can check out TryHackMe's **[Snort](https://tryhackme.com/r/room/snort)** Room, also **[deploy your own VPN](https://github.com/badgedan/free-cloud-hosted-vpn/)**.

For the rules part, learn more about **Regex**, there's a TryHackMe **[Regex](https://tryhackme.com/r/room/catregex)** room you should check it out, also google more about this topic.

## SOC Analysis

For this part, we've kicked it off with an overview of the SOC environment and why  we need the SOC, as a resource I recommend **[SOC Core Skills with John Strand](https://www.antisyphontraining.com/course/soc-core-skills-with-john-strand/)**, their Youtube channel have 3 days recordings of the training 
- **[Day 1](https://www.youtube.com/watch?v=katlU1_7Nro&pp=ygUhU09DIENvcmUgU2tpbGxzIHdpdGggSm9obiBTdHJhbmQg)**
- **[Day 2](https://www.youtube.com/watch?v=V3JKQ2WXWec&pp=ygUhU09DIENvcmUgU2tpbGxzIHdpdGggSm9obiBTdHJhbmQg)**
- **[Day 3](https://www.youtube.com/watch?v=P1pcPJ-H-7U&pp=ygUhU09DIENvcmUgU2tpbGxzIHdpdGggSm9obiBTdHJhbmQg)**
-  **[Day 4](https://www.youtube.com/watch?v=kX_eqY8S23c&pp=ygUhU09DIENvcmUgU2tpbGxzIHdpdGggSm9obiBTdHJhbmQg)**

Also do your own research on the security solutions that exist out there, such as EDRs and so on.

The SIEM solution that was used throughout the Analysis part was IBM's QRadar, to apply it into action you can check out CyberDefenders **[QRadar 101](https://cyberdefenders.org/blueteam-ctf-challenges/qradar101/)**, also I recommend learning more about how to query events and flows in QRadar you can do your own research on Ariel Query Language, and what's Ariel Database and why do we use it instead of Relational Database, also I recommend you learn more about Detection Engineering, how can you create a rule to detect an attack, you can learn more about this from TCM Security's **[Detection Engineering](https://academy.tcm-sec.com/p/detection-engineering-for-beginners)**.

Also check out **[Jose Bravo](https://www.youtube.com/@jbravovideos)**, a man who is known as a guy who knows more about QRadar than IBM itself.

You can add more to your arsenal by understanding **Web Attacks**, I recommend **[DVWA](https://github.com/digininja/DVWA)** to understand most of the Web Attacks that exist out there. 

I recommend you checking out the **[Incident Handling Phases](https://www.exabeam.com/explainers/incident-response/sans-incident-response-6-step-process-critical-best-practices/)**, taking each phase and understanding it at a deeper level, from that you can simulate an attack and apply your incident handling skills and provide a report of your findings.

Also, I recommend checking out the SOAR as a concept, and automating some of the Analyst activities, I've written an article about this you can check it out from **[here](https://github.com/badgedan/automated-qradar)**.

## SOC Engineering

For this part, mainly it's about implementation and trying it out yourself. So in this part I'm going to mention the main things that you need to do in order to understand the SOC environment at a wider level.

You can start with understanding how  SIEM works from the first place, I recommend checking out this **[IBM Video](https://www.youtube.com/watch?v=9RfsRn7m7OE&ab_channel=IBMTechnology)**, after that you should do your own research on what is **[Elasticsearch](https://www.elastic.co/guide/en/elasticsearch/reference/current/elasticsearch-intro.html)**, also you should research more on **Elasticsearch** integrations and how can it enable you more. 

Understanding how **Elasticsearch** works will enable you to insert logs, then play with it whether you want to dive in the security part of **Elasticsearch** or you just want to integrate **Elasticsearch** with other CTI integrations such as **OpenCTI** or **AlienVault**. 

So to put this into main bullet points to apply it yourself
- Setup the **ELK** stack
- Integrate CTI platforms with **Elasticsearch**
- Use light-weight logshippers such as **Fluentbit** and heavy-weight logshippers such as **Logstash** and understand the difference between them
- Be able to query on **Elasticsearch** 
- Understand **Ruby Regex**            





  










