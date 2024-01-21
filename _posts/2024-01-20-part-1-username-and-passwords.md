---
layout: post
title: Hacking your account Part 1- Username and passwords
readtime: true
tags: [cybersecurity]
author: Eugene Wong
thumbnail-img: "assets\img\blog\blog_20240120_hackimage.png"
---

### Quick read

- Hackers are motivated to get into your accounts for monetary purposes such as scamming the people you know, selling your details, applying for credit in your name, hired to target you or use your device and account as part of a larger and evil plan.
- There are three general methods for obtaining your username and password- purely guessing (a.ka. brute forcing), giving it up yourself (e.g. social engineering, getting scammed, writing it down) and getting into the database that stores your username and password.
- The best way to defend yourself is to make your passwords are long and use a combination of upper- and lower-case letters, numbers and symbols. Also remember to activate multi-factor authentication for further protection.
- You can use passphrases and password managers to help you remember them.

---

Yes and no, hacking an account is somewhat like in the movies. Yes, you do need to click lots and type lots before the account details are obtained. No, it is not that simple and fast- unless the details were already hacked and sold on the dark web.

The aim here is to help you understand why accounts get hacked, how do they do it, and how they are linked to common cyber security practices (a.k.a. cyber hygiene) that us white hat hackers keep reminding everyone to adopt.

### Why would hackers want to get into your account?

Just because you’re not a political figure, someone famous or a millionaire, doesn’t mean you’re not a target. In fact, it’s because you’re not a public figure that’s why it’s better. There are many reasons why hackers want to get into your account:

- **Scam others for money**- This is probably the most common. We all know friends or family members who’s been a victim of this. After getting into your account, they pretend to be you and ask your friends and family members for money. Or, they change your bank details to theirs, and re-direct the details to a bank account that they can access the funds.
- **Use your details to steal your identity**- A more organised and complicated reason, but one with a larger payoff, and less risk. Every account has little tidbits to be collected and compiled together. Your full name, date of birth, address, secret questions and answers, your daily activities posted on social media and your routines, pictures, where you work, your family members and their names, the gym you go to, the exercise route you take… you get the idea. After which, the details either get used by them or sold on the dark web. All good information to use for applying for a bank loan in your name, credit card or even to buy a house.
- **Sell your account details**- compromised accounts can be sold on the dark web. Hackers usually do the hard work and then sell it to scammers. You won’t know that your account has been compromised until later down the track.
- **Someone’s hired them**- someone who’s got something against you and has paid them good money to cause a little trouble. I’ve seen this in my other life as a private investigator. Harassment, intimidation and cyber stalking are the most common reasons.
- **Use your device to do their bidding for more evil things**- infiltrating and accessing your account or device to do more things. If it’s your device, placing malware to essentially turn your device or account into a zombie to the hackers bidding. This is known as a bot-net, and the hacker can gain more impact by using your device to mask their own identity (the police knock on your door instead of theirs), execute malicious code to spread all at once and to all your contacts (imagine 100s of compromised device each with hundreds of contact details- that’s a lot of people to send their malware to).

### How are accounts hacked?

Disclaimer- this won’t be a step-by-step guide on hacking accounts. Of course, this is the complicated part. There are many ways to obtain your username and passwords to compromise your account. However, from experience, most of them can be grouped into the three categories below.

#### 1. **Guessing/ brute-forcing**

This is the method you see on TV and movies. A brute-forcing tool is used to run through the thousands and millions different combination. The easiest is where a dictionary of common usernames and passwords are tried until it hits the right one. That is why you shouldn’t use commonly known passwords like password1, abcde, 12345 etc. And trust me, the wordlist containing tens of thousands of the world’s most common username and passwords is publicly downloadable from the internet (yes, the normal internet- not the dark web). This is the reason you should always change your default username and password.

The other is where the tool tries every character and number available. This takes a long time and requires a lot of processing power. Think about it going through a, b, c… A, B, C…1, 2, 3… so on and so forth. That is why the longer your password is, the longer time this will take.

#### 2. **Giving it up yourself**

Clicking a link and entering your details, writing it down, saving it on your desktop in a text document, using the same password for every single account, using information about yourself that is publicly available (e.g. name, date of birth, year of birth, street name, suburb ←common ones found on social media), telling someone your username and password, using easy to guess usernames and passwords… the list just goes on.

#### 3. **Storage of the account details are unsecured and compromised**

Unfortunately, you can’t defend yourself against this. Username and account details have to be stored in a database so that when you enter your details, the device or software can compare it to a list of authorised users. Database storage used by software and system engineers these days are getting a lot more complicated and secured with stronger algorithms. Despite this, they still need to be secured and guess what… yes… username and password. This can get leaked or hacked.

### What can you do to make it harder?

Now that you have a better insight of why hackers spend the time doing such things and how they do it, you have a better insight as to how you can protect yourself.

#### 1. Use a passphrase

Passphrases are random words stuck together. It increases the length of your password which increases the time it takes to brute force your password. Furthermore, publicly known personal information isn’t used from you giving it up yourself.

Take “col123456” the 9th most common password in 2022 according to [NordPass](https://nordpass.com/most-common-passwords-list/).

![nordvpn. 9th common password. col123456.](/assets/img/blog/blog_20240120_9th-common-password.png)

The strength of the password is 56% according to [passwordmeter.com](https://passwordmeter.com/) as seen below.

![password strength of col123456](/assets/img/blog/blog_20240120_password-col123456.png)

Now using a random word generator to obtain the passphrase “RobotWarmEggLostSheep”. You can see that strength of the passphrase according to [passwordmeter.com](https://passwordmeter.com/) is now 81% due to its length below.

![password strength of RobotWarmEggLostSheep](/assets/img/blog/blog_20240120_passphrase-RobotWarmEggLostSheep.png)

Everyone struggles to remember their password with their own personal information, let alone random words in a phrase. Another recommended way is to use a sentence from a book. Let’s use the first line in Alice in Wonderland- “AliceWasBeginningToGetVeryTiredOf”, the strength is now 100% as seen below. You just need to pull your book out to enter in your password.

![password strength of the first line in Alice in Wonderland](/assets/img/blog/blog_20240120_passphrase-aliceinwonderland.png)

Of course, the best passwords are:

- long
- uses a combination of upper and lower case letters
- uses numbers
- uses symbols

#### 2. Use a password manager

Password managers allow you to generate random, complicated, long passwords AND help you remember them. That means that you can’t give it away yourself and it takes REALLY long to crack them. You just need to remember one very complicated password to access the password manager such as the passphrase methods mentioned above.

Pick password managers that encrypts and store your username and password database on your computer rather than store it on the cloud or their servers, such as the ones offered by your browser- Chrome, Edge, Safari. Although storing it on the cloud and their servers is a lot more convenient such that the details are auto filled when you log onto the website, the database can get compromised very easily. Storing it on your device is always safer.

#### 3. Use multi-factor authentication (MFA)

Of course, increasing the number of steps to get into your account will frustrate hackers. It even frustrates you getting into your own account. How many times have you logged in with your username and password and then a code is sent to your phone. And you roll your eyes because you now have to get up and go find your phone. MFA increases the time it takes to brute force and protects you against when the database of username and passwords is compromised.

Nevertheless, this is not as secure anymore. I recently helped someone who had their myGov account hacked. Unfortunately, they were a victim of scammers and clicked a link sent by SMS. They were re-directed to a fake myGov website where they entered their username and password (at the same time the information was submitted the details to the real myGov website to prompt for a code sent to be sent their phone). The person then entered the code into the fake website, which allowed the hackers to enter their myGov account.

Furthermore, a really determined hacker could just hack your phone and clone it as part of a bot-net. They can then see everything that happens on your phone.

### Conclusion

There is ALWAYS a tradeoff between SECURITY and CONVENIENCE. I hope that now that you know the motivation and general methods of why hackers want to get your details, you keep up your cyber hygiene.

- use a passphrase
- use a password manager
- activate multi-factor authentication.

Stay safe, stay secured peeps!
