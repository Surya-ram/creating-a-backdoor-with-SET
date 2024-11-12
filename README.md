### Date:
# Ex-7: Creating-a-backdoor-with-SET
creating a backdoor with SET - Ethical Hacking Techniques course

## AIM:
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
The command sudo setoolkit in the prompt gives menu with set prompt:</br>
![1)](https://github.com/user-attachments/assets/3a62db03-8c25-4f74-b41b-f5d79dc3eb39)
</br>
 It displays the following menu and select 2 for Website Attack Vectors:</br>
![2)](https://github.com/user-attachments/assets/807635b3-5f0a-4f72-9a90-725cee27ada7)
</br>
 The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:</br>
![3)](https://github.com/user-attachments/assets/00695b9f-2047-48d0-ac07-9d69ac41512a)
</br>
 The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:</br>
 ![image](https://github.com/user-attachments/assets/b950b9ea-52f9-4da6-8941-0c2cb0612cfb)
</br>
 It shows the following screen in which the ip address of the attacker need to be given which is the default value:</br>
 ![image](https://github.com/user-attachments/assets/087db1a0-54a4-4ec9-80e2-da3127477311)

 </br>
 It shows the following screen in which the option Google can be selected:
</br>

![image](https://github.com/user-attachments/assets/8f650235-f286-4619-ae80-12dd815b0462)

</br>
 SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:</br>
 
 ![image](https://github.com/user-attachments/assets/1f4867c4-92dc-49a5-828d-55de05b3a3f8)
</br>
 In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password </br>
 
![image](https://github.com/user-attachments/assets/4c738469-6c93-473f-8002-89ab0f92513b)


 </br>
 SET logs the information regarding the Google credentials:
</br>

![image](https://github.com/user-attachments/assets/42f39566-b52f-4d7b-b3f3-c5222b9db6b6)

</br>
 
 SET logs the information in the xml file under /root/.set directory:
 </br>
 ![image](https://github.com/user-attachments/assets/ff3bd5f6-9fce-4646-97b6-f7cf20333385)

## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully






## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
