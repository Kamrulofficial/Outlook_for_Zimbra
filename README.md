# How To Configure Microsoft Outlook for Zimbra
Zimbra is nowadays is one of the most common Open source email collaboration solutions found on most enterprise setups. I’ll cover its installation for a single server and multi-server setups in the upcoming articles. On the other hand, Microsoft Outlook is the defacto email client in the Microsoft space which helps millions of users connect all their email accounts, calendars, and files in one convenient spot.

Configure Microsoft Outlook for Zimbra

I assume you already have installed Microsoft Outlook application. Follow these steps to get it configured.

Outlook mail and Open new window will open. Select manual and click next.
![image](https://user-images.githubusercontent.com/44496738/191179960-50587f2c-9eea-4939-aa10-2d3d1a526f5c.png)

On the next window, choose service type of POP or IMAP and click next.

![image](https://user-images.githubusercontent.com/44496738/191180360-bd261d3b-dbbc-4b72-8bd6-887b8e28814e.png)

You’ll be prompted for your email account information. Fill it with the correct info. For account type, you can do IMAP or POP3 depending on your requirements. For me, I’ll go with IMAP.
<h3>Options to fill:</h3>
<p><strong>Your Name</strong>: Enter your name which will appear when you send out an email<br><strong>Email address</strong>: Enter your full email address Account type: Select IMAP<br><strong>Incoming mail server</strong>:&nbsp;hostname of Zimbra mail server (MX record value)<br><strong>Outgoing mail server</strong>:&nbsp; hostname of Zimbra mail server<br><strong>User Name</strong>: Enter your full email address<br><strong>Password</strong>: Enter your correct password.</p>
<br>
 <strong>Incoming mail server:  </strong> mail.Domain.com <br>
 <strong>Outgoing mail server:  </strong> Mail.Domain.com


![image](https://user-images.githubusercontent.com/44496738/191180722-7eefd444-5a65-4749-aa62-05530603e590.png)

Once you have supplied the correct information click on  <strong> more settings  </strong> the internet email dialogue box will appear. Under the outgoing server tab ensure you check “my outgoing server (SMTP) requires authentication”.

<br>Next click on the <strong> advanced tab. </strong>
<br>Incoming Server: Zimbra server hostname<br>Protocol: IMAP<br>Port <strong>993</strong> (SSL Enabled)<br>Outgoing server: Zimbra&nbsp;hostname | or relay server if any<br>Protocol: <strong>SMTP</strong><br>Port <strong>465</strong> (SSL Enabled)
![image](https://user-images.githubusercontent.com/44496738/191182516-e369ea18-6b2f-4c95-a682-d07708b7d481.png)
<br>
Once the above information is supplied click on ok.
<br>
Next, your account will try login and send a test email. If successful you will see the below.

<br>
You’re set to start sending and receiving emails on your Outlook application.
<br>
Tags:

* Configuring Microsoft Outlook for IMAP and POP3
* Configure Outlook to work with Zimbra
* Zimbra and Outlook integration
* Configure Outlook to send and receive emails through Zimbra

<br>
Thanks For  Advance </br>
<br> # ELITE KAMRUL
