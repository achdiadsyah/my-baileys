# Baileys-Simple
<div align="center">
    <a href="https://github.com/achdiadsyah">
        <img title="Author" src="https://img.shields.io/badge/Author-Ryan Achdiadsyah-black.svg?style=for-the-badge&logo=github" alt="">
    </a>
    </p>
    <a href="https://github.com/achdiadsyah?tab=followers">
        <img title="Followers" src="https://img.shields.io/github/followers/salman0ansari?color=black&style=flat-square" alt="">
    </a>
    <a href="https://github.com/achdiadsyah/my-baileys/stargazers">
        <img title="Stars" src="https://img.shields.io/github/stars/achdiadsyah/my-baileys?color=black&style=flat-square" alt="">
    </a>
    <a href="https://github.com/achdiadsyah/my-baileys/network/members">
        <img title="Forks" src="https://img.shields.io/github/forks/achdiadsyah/my-baileys?color=black&style=flat-square" alt="">
        </a>
    <a href="https://github.com/achdiadsyah/my-baileys/issues">
        <img title="Issues" src="https://img.shields.io/github/issues/achdiadsyah/my-baileys?color=black&style=flat-square" alt="">
    </a>
</div>

### Important Note

This library was originally a private project  and is in no way affiliated with or endorsed by WhatsApp. Use at your own discretion. Do not spam people with this. We discourage any stalkerware, bulk or automated messaging usage.

Baileys does not require Selenium or any other browser to be interface with WhatsApp Web, it does so directly using a **WebSocket**. 
Not running Selenium or Chromimum saves you like **half a gig** of ram :/ 
Baileys supports interacting with the multi-device & web versions of WhatsApp.

### Library and Stack

1. NodeJS 14.x.x
2. [WhiskeySocket](https://github.com/WhiskeySockets/Baileys)
3. Express Js


### How To Use and Install
```
git clone https://github.com/achdiadsyah/my-baileys.git
```
```
npm install
```
```
npm run start
```

### Scan QR

```
go to : http://your_ip_or_url:8000/scan

        or

QR will be appear in terminal
```

### Send Text Message or Media to whatsapp user
METHOD : **POST**
```
URL : http://your_ip_or_url:8000/send-message

- number (must be with country code like : 62xxxxxxx)
- message (your text to send)
- file_dikirim (must be accessible URL like : https://your_url.domain/blablabla.jpg)
```

### Send Text Message or Media to whatsapp group
METHOD : **POST**
```
URL : http://your_ip_or_url:8000/send-message

- id_group (must be with @g.us code like : 123xxxxxxxxxxxxx@g.us)
- message (your text to send)
- file_dikirim (must be accessible URL like : https://your_url.domain/blablabla.jpg)
```

---
### NOTE !!!
- Single Device Online
- Session will store inside a folder "baileys_auth_info" (it automaticaly create a folder)
- Not using and RDBMS juts a json file.
- I can't guarantee or can be held responsible if you get blocked or banned by using this software. WhatsApp does not allow bots using unofficial methods on their platform, so this shouldn't be considered totally safe.

### LEGAL NOTICE
-   This code is in no way affiliated, authorized, maintained, sponsored or endorsed by WA (WhatsApp) or any of its affiliates or subsidiaries.
-   The official WhatsApp website can be found at https://whatsapp.com. "WhatsApp" as well as related names, marks, emblems and images are registered trademarks of their respective owners.
-   This is an independent and unofficial software Use at your own risk.
-   Do not spam people with this.