
# How to secure your accounts after you got compromised.

“What to do when you are compromised and got your account back. Assume all your devices are still compromised and key logged. These steps are post-compromise for regular average users.”

## Summary
- Install a fresh operating system and fully update it.
- Have a Antivirus Total Security with Firewall
- Install uBlock Origin and Firefox/Chrome Browser
- Use a Password Manager.
- Register new email for specific purposes.
- Use a Password Manager to manage your credentials.
- Use Two Factor Authentication (2FA) and isolated email accounts.
- Enable login notification for suspicious activity.
- Spotting Phishing: [https://identity.utexas.edu/everyone/spotting-a-phishing-email](https://identity.utexas.edu/everyone/spotting-a-phishing-email)
- Don't share informations regarding your personal accounts that shouldn't pe public.
- Use VPN on public networks.

## Baselining

 - List all Devices that you are using including Phones, Computers and Tablets.
 
 - List all the accounts that you have, where are they login.
 
 - How much public information is available through public searches.
 
 - What are your attack surfaces.
 
 - How are these accounts connected.

## Hardening

### Computer 

- Reinstall your operating system and don’t restore from backup.

- Update your operating system and encrypt your devices.

- Purchase a Yubikey Multifactor Authentication Device.

- Enable 2 Factor:  [https://finance.yahoo.com/news/a-cheat-sheet-for-securing-your-accounts-with-two-step-94483496354.html](https://finance.yahoo.com/news/a-cheat-sheet-for-securing-your-accounts-with-two-step-94483496354.html)
#### Malware Scan

Run a malware scan.

- **HitmanPro Malware Removal Tool**: [https://www.hitmanpro.com/en-us/hmp.aspx](https://www.hitmanpro.com/en-us/hmp.aspx)

- **Malwarebytes**: [https://www.malwarebytes.com/mwb-download/](https://www.malwarebytes.com/mwb-download/)

- **Malwarebytes Anti-Rootkit BETA**: [https://www.malwarebytes.com/antirootkit/](https://www.malwarebytes.com/antirootkit/)

Install paid Antivirus with Total Security.

- **Bitdefender Total Security 2020**: [https://www.bitdefender.com/solutions/total-security.html](https://www.bitdefender.com/solutions/total-security.html)

- **ESET Smart Security**: [https://www.eset.com/int/home/smart-security/download/](https://www.eset.com/int/home/smart-security/download/)


### Mobile Devices
Uninstall some unused apps.

- **Android** - [https://www.digitaltrends.com/mobile/how-to-delete-apps-in-android/](https://www.digitaltrends.com/mobile/how-to-delete-apps-in-android/)

- **Apple Devices** - [https://support.apple.com/en-ca/guide/iphone/iph248b543ca/ios](https://support.apple.com/en-ca/guide/iphone/iph248b543ca/ios)


### Router
In some cases, the attacker is closer than you think. - [https://www.forbes.com/sites/thomasbrewster/2020/02/28/fbi-warned-of-fraudsters-paradise-up-to-130000-hacked-asus-routers-on-sale-for-a-few-dollars/#20c8c7222009](https://www.forbes.com/sites/thomasbrewster/2020/02/28/fbi-warned-of-fraudsters-paradise-up-to-130000-hacked-asus-routers-on-sale-for-a-few-dollars/#20c8c7222009)

- Guide: [https://www.comparitech.com/blog/information-security/secure-home-wireless-network/](https://www.comparitech.com/blog/information-security/secure-home-wireless-network/)

- Disable services that you are not using. 

- Check your router settings, change it to stronger password.

- Check if web interface in exposed to the internet, disable UPNP.

- Remove forwarded ports that are not necessary.

- **OpenDNS** blocks phishing websites that try to steal your identity and login information by pretending to be a legitimate website. Surf the Web with confidence. - [https://use.opendns.com/](https://use.opendns.com/)

## Change Password on your Email Accounts

- Generate Random Different Passwords.

- Use Password manager like **Bitwarden** or **LastPass**.

- Use unique security questions and answers. Your dog's name are public information.

## Email Isolation

 - Create three email address (Social, Banking, Personal)
 
 - Example: cxSocialAccount@gmail.com, cxBanking@gmail.com, cxPersonal@gmail.com
 
 - The public email shouldn't be connected to important accounts.
 
 - Password Backups should be printed and saved in a vault, and in an encrypted container.
 
 - Recovery Email should be private and as secure as the other emails.
 
## Phone Security

- Enable Pin, Password or Fingerprint.

- Enable Disk Encryption.

## Sim Card Security

**Sim Card Swapping** - A SIM swap scam is a type of account takeover fraud that generally targets a weakness in two-factor authentication and two-step verification in which the second factor or step is a text message or call placed to a mobile telephone. [https://www.cnet.com/how-to/sim-swap-fraud-what-it-is-why-you-should-care-and-how-to-protect-yourself/](https://www.cnet.com/how-to/sim-swap-fraud-what-it-is-why-you-should-care-and-how-to-protect-yourself/)

- Enable Sim Card Pin. 

- Strong password for your Phone Online Account with Two Factor.

- Call phone service provider and put a note.

- Don’t allow number porting unless done in store with two pieces of ID.

- Don’t allow sim card swapping and new activation unless done in store.

- Create a unique security question, add note prevent guessing.

## Email Security

Read: [https://twofactorauth.org/](https://twofactorauth.org/)

### Renew Backup Codes 

Compromised backup codes can still be used to gain access to an account, without having access to 2 Factor Devices like SMS or email. An attacker can use this, get back in. - [https://www.techrepublic.com/article/bypass-two-step-authentication-with-app-passwords/](https://www.techrepublic.com/article/bypass-two-step-authentication-with-app-passwords/)

- **Revoke Gmail Backup Codes**: [https://www.techrepublic.com/article/how-to-retrieve-your-google-2fa-backup-codes-and-make-more/](https://www.techrepublic.com/article/how-to-retrieve-your-google-2fa-backup-codes-and-make-more/)

- **Revoke Yahoo Account Key**: [https://help.yahoo.com/kb/SLN25781.html](https://help.yahoo.com/kb/SLN25781.html)

- **Revoke Apple Rescue Email**: [https://support.apple.com/en-us/HT201356](https://support.apple.com/en-us/HT201356)

### 2 Factor Authentication
Two Factor Authentication can prevent further access to an account if setup properly. https://nakedsecurity.sophos.com/2018/12/21/more-phishing-attacks-on-yahoo-and-gmail-sms-2fa-authentication/

**Enable Two-Factor Authentication (2FA)**
- [https://www.theverge.com/2017/6/17/15772142/how-to-set-up-two-factor-authentication](https://www.theverge.com/2017/6/17/15772142/how-to-set-up-two-factor-authentication)

**Enable Two-Factor Authentication (2FA) using Duo Mobile**
- [https://guide.duo.com/](https://guide.duo.com/)
- It provides Call, SMS and Push notification.

### Persistent Backdoor Access

Email forwarding generically refers to the operation of re-sending an email message delivered to one email address to a possibly different email address(es). For example: Attacker can force your Facebook Account, that reset link will be forwarded both to your account and the backdoor email. https://www.impsolutions.com/news-and-events/blog/how-office-365-email-hack-cost-millions-and-how-you-can-avoid-same-fate

**Stop Automatic Email Forwards**

- [https://help.parseur.com/en/articles/3565554-stop-automatic-email-forwards](https://help.parseur.com/en/articles/3565554-stop-automatic-email-forwards)

**Sign out of Email From Multiple Devices**

Failing to revoke any active sessions can still give the attacker a foothold in that account. Some services keeps the session even after changing your password.

- [https://time.com/4177486/gmail-remotely-sign-out/](https://time.com/4177486/gmail-remotely-sign-out/)

- [https://www.wikihow.com/Find-Out-Who-Hacked-Your-Yahoo-Email](https://www.wikihow.com/Find-Out-Who-Hacked-Your-Yahoo-Email)

**Delete Email Application Passwords**

Application passwords that are generated while attacker have access to your account enables him to login to an 'email' app with that account. Bypassing 2 Factor all together.

**Gmail** – Remove App Passwords

- [https://support.google.com/accounts/answer/1070455?hl=en](https://support.google.com/accounts/answer/1070455?hl=en)

**Yahoo** - Revoke App Passwords

- [https://www.lifewire.com/manage-app-passwords-imap-pop-yahoo-1174448](https://www.lifewire.com/manage-app-passwords-imap-pop-yahoo-1174448)

**Apple** – Remove a device from the list.

- [https://support.apple.com/en-ca/HT205064](https://support.apple.com/en-ca/HT205064)



## Social Media Accounts

Allowing indexing of your  social media page reveals some important more information that you want to, also adjust your privacy controls.

### Disable Search Engine Indexing on your Social Media Accounts
- https://www.clickonf5.org/social/howto-hide-facebook-profile-indexing-search-engines-google/6051
- https://help.twitter.com/en/safety-and-security/remove-twitter-profile-from-google-search

### Adjusting Privacy Settings
- [https://identity.utexas.edu/everyone/how-to-manage-your-social-media-privacy-settings](https://identity.utexas.edu/everyone/how-to-manage-your-social-media-privacy-settings)

### Facebook

**End all Facebook Sessions**

-  [https://www.howtogeek.com/269854/how-to-see-other-devices-logged-into-your-facebook-account/](https://www.howtogeek.com/269854/how-to-see-other-devices-logged-into-your-facebook-account/)

**Revoke App Permissions**

- [https://www.imore.com/how-to-revoke-facebook-app-permissions](https://www.imore.com/how-to-revoke-facebook-app-permissions)

### Snapchat

**Forget Snapchat Linked Device**

- [https://support.snapchat.com/en-US/a/forget-devices](https://support.snapchat.com/en-US/a/forget-devices)

**Revoke Connected Apps**

- [https://support.snapchat.com/en-GB/a/remove-connected-app](https://support.snapchat.com/en-GB/a/remove-connected-app)

### Instagram

**Remote Logout**

- [https://www.mashnol.org/log-out-instagram-from-all-devices-remotely-iphone/](https://www.mashnol.org/log-out-instagram-from-all-devices-remotely-iphone/)

**Remove Connected Apps**

- [https://thepreviewapp.com/remove-apps-connected-to-instagram-account/](https://thepreviewapp.com/remove-apps-connected-to-instagram-account/)

## Using Public Wifi

- DON'T. They are very unsecure, but if you really need to use a VPN like **NordVPN** or **PIA (Private Internet Access)**
- [https://www.howtogeek.com/133680/htg-explains-what-is-a-vpn/](https://www.howtogeek.com/133680/htg-explains-what-is-a-vpn/)

## Banking Credentials
If your banking credentials got compromised and identity is stolen.

- Visit the bank and ask for a new card, put a note and inform them about the incident.

- File a police report right away.

- Change password and use the newly created bank email.

- Enable Two Factor (2FA).

- Set unique security questions and answers.

### Enable Credit Card Monitoring
- [https://www.winknews.com/2020/02/12/freezing-your-credit-report-can-help-protect-your-money-and-credit/](https://www.winknews.com/2020/02/12/freezing-your-credit-report-can-help-protect-your-money-and-credit/)

### Credit Freeze
- [https://www.creditcardscanada.ca/education-centre/fraud-identity-theft/pay-use-credit-monitoring-services/](https://www.creditcardscanada.ca/education-centre/fraud-identity-theft/pay-use-credit-monitoring-services/)
