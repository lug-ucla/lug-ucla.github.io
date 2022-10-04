 **IMPORTANT: PLEASE CHOOSE A STRONG PASSWORD FOR YOUR EMAIL ACCOUNT** 

[![img](https://linux.ucla.edu/wiki/images/thumb/3/34/Image.png/300px-Image.png)](https://linux.ucla.edu/wiki/index.php/File:Image.png)

Some hacking attempts on our email server

 **WE GET SEVERAL BRUTE FORCE ATTEMPTS EVERY DAY. IF THE  HACKERS GET IN TO YOUR EMAIL ACCOUNT THEY WILL SEND SPAM AND THE CS  DEPARTMENT WILL GET MAD AT US.**  **Please use a secure password, otherwise we might have to restrict access to only people on the UCLA VPN.**

## Logging in

I am using the following settings with Thunderbird to get in. I haven't  tried it with another email client but you are welcome to.

SMTP: 

Server Name: mail.linux.ucla.edu 

Port: 587 

[![img](https://linux.ucla.edu/wiki/images/thumb/9/9b/Hackerman.png/300px-Hackerman.png)](https://linux.ucla.edu/wiki/index.php/File:Hackerman.png)

Look at all the hackers getting banned for too many failed login attempts!

Authentication method: Normal password 

Connection security: STARTTLS 

IMAP: 

Server Name: mail.linux.ucla.edu 

Port: 993 

Authentication method: Normal Password 

Connection security: SSL/TLS 

## Changing your password

To change the password, please ssh into your web server and ssh to [your  username]@10.0.0.10. Then use passwd to change your password.

(Yes we know, this is a pretty crappy and inelegant solution, but it's good enough for now)
