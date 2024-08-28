# Fuzzing Lab for CySA+

## Goal:
Using the Damn Vulnerable Web Application (DVWA) as a test subject and pretending it is an insecure application hosted in our environment, perform some dynamic software analysis on it. This will teach me fuzzing techniques, the value of secure coding practices, and what potential attacks applications may be exposed to when ignoring those practices.
## Skills:
- Learning dynamic analysis techniques
- Familiarizing myself with Burp Suite
- Learning the use of proxy servers in software assessment/attacks
- Practicing Linux (while setting up DVWA in Kali)
## Tools Used:
- Kali Linux
- Burp Suite
- DVWA (Damn Vulnerable Web Application)
## Screenshots:

### _1. Installation process using Linux (and a bit of troubleshooting afterwards)_
![Installing_DVWA](https://github.com/user-attachments/assets/324d42f6-ff07-4700-8908-85c5aa0d8649)


### _2. Finally got it working!_ 😃
![DVWA_Tested](https://github.com/user-attachments/assets/53e4dbf1-ce9f-46a0-9322-21bd8c7e008b)


### _3. Burp proxy captures the outbound traffic before it reaches the web application_
![Burp_capture](https://github.com/user-attachments/assets/5a551566-8bd6-47e1-bb19-fc43726e9317)


### _4. Setting variables..._
![Burp_positions](https://github.com/user-attachments/assets/8ac3598a-d92c-4986-9af3-05ed61784032)


### _5. Configuring payload..._
![Burp_payload](https://github.com/user-attachments/assets/33c7e10f-cb81-4972-b7c8-fb09e23d33b5)


### _6. Now we strike!_ 🥷
![Burp_attack](https://github.com/user-attachments/assets/9b68a7b3-5239-4030-b916-30ea7813ee37)


### _7. Results of one of the payloads, demonstrating the need for input validation_
![Burp_result](https://github.com/user-attachments/assets/7a1b32ee-2dbf-4af3-b2a3-c02f536ed16e)


### _8. Playing around with settings, trying a large number of random #s_
![Burp_result2](https://github.com/user-attachments/assets/75cd9090-b7b1-444f-829a-2d15aacdfbcc)



#### A pretty small lab for today, but it was fun to mess around with Burp Suite. Now that I have it all set up, I'll break DVWA even harder in the future! Looking forward to more fun little projects as I continue to develop my cyber skills 🚀
