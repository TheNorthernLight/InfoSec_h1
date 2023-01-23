# InfoSec_h1
h1 First steps
Become a hacker, step 0

x) Read and summarize. (This subtask x does not require tests with a computer. Some bullets per article is enough for your summary)
Hutchins et al 2011: Intelligence-Driven Computer Network Defense Informed by Analysis of Adversary Campaigns and Intrusion Kill Chains, chapters Abstract, 3.2 Intrusion Kill Chain and 3.3 Courses of Action



Karvinen 2020: Command Line Basics Revisited

a) Bandit oh-five. Solve Over The Wire: Bandit the first five levels (0-4).



b) Bullseye. Install Debian 11-Bullseye virtual machine in VirtualBox. (See also: Karvinen 2021: Install Debian on VirtualBox)



c) WebGoat. Install WebGoat practice target. (See also: Karvinen 2021: Install Webgoat 8 - Learn Web Pentesting)

Install Webgoat 8 - Learn Web Pentesting

WebGoat is a beginner friendly practice target for web penetration testing.

Prerequisites

Install Java (and some helpful tools)

    $ sudo apt-get update
    $ sudo apt-get -y install openjdk-11-jre ufw wget bash-completion
    
Enable firewall.

    $ sudo ufw enable  
    
Install and Run WebGoat

Download and run Webgoat 8:

    $ wget https://terokarvinen.com/2020/install-webgoat-web-pentest-practice-target/webgoat-server-8.0.0.M26.jar
    $ java -jar webgoat-server-8.0.0.M26.jar

Register

write in the browser

    http://localhost:8080/WebGoat/
    
    

d) Hacker warmup. Solve these tasks on WebGoat


General: HTTP Basics


General: Developer tools



n) Voluntary bonus: Banditry. Solve Over the Wire: Bandit 5-7.




o) Voluntary bonus: My fundaments. What do you consider the fundamentals of security? What would you teach the first day?



p) Voluntary bonus: Johnny Tables. Solve Webgoat: A1 Injection (intro).




q) Voluntary multi-week bonus, requires programming: Ptacek et al: Cryptopals.





