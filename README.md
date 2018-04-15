
# Project 9 - Honeypots 

Time spent: **  ** hours spent in total

> Objective: Setup a honeypot and intercept some attempted attacks in the wild.

> Include the following details:

Which Honeypot(s) you deployed:

I deployed Dionaea over HTTP("Ubuntu Dionaea") - a honeypot used to trap malware samples. 


Any issues you encountered:

The instructions were clear and straightforward, however I still ran into a few issues during the set up process. During milestone 1, the "firewall creation" process was taking a long time and I was unable to access the MHN admin console in my browser during milestone 4.This was my first time using google cloud program so I had the opportunity to understand the different tools and how to initialize it. I also was having a hard time using nmap. For some reason, I was unable to brew install nmap to pass it the IP of the honeypot VM.


A summary of the data collected: number of attacks, number of malware samples, etc:

Number of Attacks : 988

 Top 3 Attacker IPs: 
 35.193.140.16 (986 attacks)
 77.72.82.16 (1 attacks)
 177.188.249.244 (1 attacks)
 
 Please see the attached images for the attacks report - summary report of all the attacks. 
<img src='Screen Shot 2018-04-15 at 3.34.02 PM.png'/>
<img src='Screen Shot 2018-04-15 at 3.33.47 PM.png'/>


Any unresolved questions raised by the data collected:

I think it would be interesting to observe the data collected as the the number of days since the original date of deployment increased. 

Additionally, include a json export of the data you collected in the repo. Please see below for the file. 

Session.json : ![Click Here](https://github.com/Sudeepti-S/CodePath9/blob/master/session.json)
