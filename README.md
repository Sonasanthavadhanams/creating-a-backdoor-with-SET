# creating-a-backdoor-with-SET
creating a backdoor with SET - Ethical Hacking Techniques course

# AIM:
To Create a backdoor with Social Engineering Toolkit (SET)

## DESIGN STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode


### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:

Open terminal and try execute some kali linux commands

## EXECUTION STEPS AND ITS OUTPUT:
Social Engineering attacks are the various cons used by the hackers to trick people into providing sensitive data to the attackers. 
The command sudo setoolkit in the prompt gives menu with set prompt:
## OUTPUT

<img width="1920" height="923" alt="image" src="https://github.com/user-attachments/assets/ac49f599-11b4-4853-961e-6f8225c2bf10" />


The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:
## OUTPUT

<img width="1920" height="923" alt="image" src="https://github.com/user-attachments/assets/68bfac26-d3c9-4560-983e-6149d320ab1d" />


It displays the following menu and select 2 for Website Attack Vectors:
## OUTPUT

<img width="1920" height="923" alt="image" src="https://github.com/user-attachments/assets/02058083-ef5f-483f-8e30-dc730cbe55b2" />


The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:
## OUTPUT

<img width="1248" height="482" alt="image" src="https://github.com/user-attachments/assets/4a84c2ef-1b4f-4c68-9be7-0b351f301ce0" />


It shows the following screen in which the ip address of the attacker need to be given which is the default value:
## OUTPUT


<img width="1020" height="606" alt="image" src="https://github.com/user-attachments/assets/9552895a-721c-45e2-abc6-a4e2ec750b8f" />


It shows the following screen in which the option Google can be selected:
## OUTPUT


<img width="1238" height="596" alt="image" src="https://github.com/user-attachments/assets/e983190f-62af-4945-8cd6-3153a7350e39" />



SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:
## OUTPUT


<img width="1920" height="923" alt="image" src="https://github.com/user-attachments/assets/cf1b0c6a-0341-4cae-a1a2-3aeab858393e" />


In windows IE, on giving the url http://192.168.1.2 (use appropriate IP address), the fake Google page is displayed. The victim can enter the username and password
## OUTPUT

<img width="1680" height="944" alt="Updated terminal username – 26 Nov 2026, 9 49 am" src="https://github.com/user-attachments/assets/f5ed89a2-990b-4c4b-8ba6-c375c97a9d4f" />

SET logs the information regarding the Google credentials:
## OUTPUT
<img width="1680" height="944" alt="Updated terminal username – 26 Nov 2026, 9 51 am" src="https://github.com/user-attachments/assets/ff8e23df-a072-4c3e-aaca-5253cbe1838c" />



SET logs the information in the xml file under /root/.set directory:
## OUTPUT

<img width="1680" height="944" alt="Updated terminal username – 26 Nov 2026, 9 53 am" src="https://github.com/user-attachments/assets/6fcf6658-fc25-4719-8a86-ed556963907b" />











## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
