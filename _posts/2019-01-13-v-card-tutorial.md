---
layout: post
title: "How to have all your contacts on one safe place!"
---

> This post is a re-broadcast of one of my old articles, originally published on 30th of April 2018.

In this article you will find out how to manage your contact list using V-cards, how to make them, import your other contacts into your own list and export them into all your devices and why using them is more private and secure than a cloud based service.



# Introduction to V-cards.

Keeping in touch with old fiends can be a major pain, your closest friends might be on facebook but your old coworker is on telegram, your grandparents don't bother with technology non-scene and you can only contact them on the phone.

Every service or company like facebook, Gmail, Outlook and your smart-phone are competing for being the most convenient way of keeping in touch, this endless competitions only serves to fragment your contact list. All your work contacts are on some old email account, your old college friends are somewhere in a FB group. In other words no service is truly convenient.

If you could only go back to the old days of writing down phone numbers and emails on a reliable sheet of paper everything would be better! right? well... Old school address books are inconvenient if you have to keep them in a bag somewhere handy at all times, we can do better: **V-cards** are what you are looking for.

V-cards are simple, small files. Easy to store on a USB stick or backed up in the cloud and they can store each and every single one of your contacts in one safe and easy to read place. That means all your facebook contacts, your smarphone address book and old emails in one place.

# Will V-cards work on my device?

Yes, they are a standard since the 90's. They work on Windows computers, Apple computers, iPhones, Androids. The list goes on and on, even back to supporting dumb phones like Nokia's and Blackberry's

V-cards are as compatible and universal as it gets, services like facebook, gmail, android and iOS probably use them on the back end.

# Can I trust them?

Of course you can! V-cards are safe in the sense that they are simple plain text files that you create yourself, they will not compromise you to any computer virus like downloading a random program on the Internet will because v-cards are made and manged by you, not a random person from the Internet.

They are private in the sense that they are stored in your device and nowhere else. Other methods like using Google contacts, Facebook in general, the contacts app on your phone are always looking any changes you make, they do this out of good will to provide cloud services but the problem is that they store your private information on their insecure servers. Remember the iCloud leaks? see, apple services are not to be trusted! Google, Yahoo and Facebook use similar security measures that could be compromised in the future. Likewise they are not to be trusted.

According to the New York Times:

> Back in 2014 hackers stole private information of over 500 million users from yahoo servers, including contact information like their full names, addresses, telephone numbers and passwords. 

> *[Source](https://www.nytimes.com/2016/09/23/technology/yahoo-hackers.html), [archived source](https://archive.li/KaLEY)*


# What is a V-card and how to read and understand them?

So what are v-cards? well they are made in plain text for easy reading this files end in .vcf (short for v card file) and they read very much like and old school address book. For example: lets say I want to store the phone numbers of King Kong and Mario Bros, in that case I want something like this:

```
first contact begins here


king kong

cellphone number is 123...

first contact ends here

second contact begins here

mario bros

home phone is 321..

second contact ends here

.
.
.
.
etc
```

We are writing this because we actually mean what's shown in the image below:

![What you mean](https://i.imgur.com/1hppDxM.png)

If you look at them side by side its very easy to see the correlation because people understand address books and the concept of phone numbers, but computers are really dumb, they are truly stupid.

![big dumb dumb](https://i.imgur.com/Xoln9du.png)

So we have to hold their hand and explain them what we want them to do in the simplest way possible, meaning we have to write some code. Don't worry, this code will be super simple, no fancy variables or programing, none of that just simple code that you can easily understand and read out loud to anyone without any confusion.

This is why instead of writing in the "first contact begins here" format we will write some very simple code, we will write:

*(using capital letters on the code is necessary)*

```
BEGIN:VCARD
VERSION:3.0
FN:king kong
TEL;TYPE=CELL:123...
END:VCARD
BEGIN:VCARD
VERSION:3.0
FN:mario bros
TEL;TYPE=HOME:321..
END:VCARD
```

At the beginning we write <code>BEGIN:VCARD (then the enter key) VERSION:3.0</code> because that is the only way our dumb computer will understand <code>first contact begins here</code> and at the end we write <code>END:VCARD</code> because it means <code>first contact ends here</code>.


<code>FN:</code> is short for "**Full Name**", <code>TEL;TYPE=CELL:</code> means **This is a cellphone number** and <code>TEL;TYPE=HOME:</code> means **This is a home number**.

Vcards support saving their email, were they work at, their position, their website, birth dates and much more.

[Check this website for more information](http://www.evenx.com/vcard-3-0-format-specification), [Archived website](https://archive.li/tZGj4)

For your continence I have created a simple template that explains each type of information you can store.

# V-card template

```
BEGIN:VCARD
VERSION:3.0
N:Lastname;Surname
FN:FULL NAME GOES HERE
ORG:ORGANIZATION GOES HERE
URL:WEBSITE GOES HERE
EMAIL:EMAIL GOES HERE
TEL;TYPE=CELL:CELLPHONE GOES HERE
TEL;TYPE=HOME:HOMEPHONE GOES HERE
B-DAY:YYYY-MM-DD
NOTE:Here you can write any notes, Using "N:" is not mandatory. Coppy paste this in a text file as much as you want. Remember to save as "NAME.vcf".Order doesn't matter. Begin and end with "BEGIN:VCARD VERSION:3.0 and END:VCARD" Keep this as a reminder to you in the future. More info on the website https://archive.li/tZGj4#selection-441.10-441.20 or https://alex-esc.github.io/blog/contacts.html or the wikipedia article on https://en.wikipedia.org/wiki/VCard
END:VCARD
```

# How to make your own V-card.

## General instructions.

just copy paste the preset or start from scratch if you want on a plain text file and fill in the desired information, you can have multiple vcards inside one file, just make sure to save the document as "NAME.vcf", were you can write any title you want.

## Specific instructions with pictures.

The process on a windows computer will look like this:


First create a new simple text document like this. 

1. Go to your desired destination to save your vcard
2. right click
3. click on "New"
4. click on " Text Document"

My computer is in Spanish so your process will be on your language.

![new text file](https://i.imgur.com/gBN0Tgu.png)

5. Next you want to paste my preset and fill it in with your desired info, remember you can coppy paste it multiple times to store multiple contact on one single file, like shown below

![written vcard](https://i.imgur.com/r2JXPHJ.png)

6. then click on the save button and name your vcard, I named mine "my contact list" 

![name the document](https://i.imgur.com/43IC9vc.png)

7. then on the menu below the name box you will find a document type box, make sure to select "All documents (\*.\*)" and add ".vcf" at the end of the name of your document, remember that .cvf stands for v card file. If your document ends with anything but ".vcf" the v-card will not work.

![save as .vcf](https://i.imgur.com/eQRE8VH.png)

8. Once saved, you will see the icon change and it will look like this:

![final step](https://i.imgur.com/BkTmPbe.png)

## Get your contacts and manage them yourself. - Import and export V-cards from other services.

Well now that you know how to make your own V-card from scratch you might want to get a head start by getting all your contacts in V-card form.

Because V-cards are used universally there are may tutorials out there to import and export your contacts from any given device, here I have created a simple table with links to tutorials for several commonly used devices and for Nokia and Blackberry just to prove my point that V-cards are as compatible as it gets.

I would advise you to bookmark this page if you are interested in importing and exporting V-cards in the future, anyways here you go!

|Platform      | Import      | Export      | Import and export|
|---|---|---|---|
|Windows computer|-|-|[Instructions here](https://www.howtogeek.com/173688/how-to-export-a-contact-to-and-import-a-contact-from-a-vcard-.vcf-file-in-outlook-2013/)|
|Apple Computer|[Instructions here](https://support.apple.com/guide/contacts/import-contacts-adrbk1457/mac)|[Instructions here](https://support.apple.com/guide/contacts/export-and-archive-contacts-adrbdcfd32e6/mac)|-|
|Gmail or Google contacts|-|-|[Instructions here](http://www.techfleece.com/2013/09/13/how-to-import-multiple-vcards-vcf-files-into-gmail-or-outlook/)|
|Yahoo mail contacts|-|-|[Instructions here](https://www.wikihow.com/Export-Contacts-from-Yahoo)|
|iPhone/iPad/iPod|[Instructions here](https://www.techwalla.com/articles/how-to-import-vcf-to-an-iphone)|[Instructions here](https://www.imobie.com/support/export-iphone-contacts-to-vcard.html)|-|
|Android Phone|-|-|[For Samsung](https://www.fonepaw.com/solution/import-export-android-contacts.html) and [for all Androids](https://android.stackexchange.com/questions/41136/transfer-and-import-vcf-contacts)|
|Nokia 301 or other generic Nokia|[Instructions here](https://www.lambrospetrou.com/articles/nokia-symbian-s40-contacts-transfer/)|-|-|
|Backberry curve 9220 or other generic Blackberry|[Instructions here](https://mobiletrans.wondershare.com/contacts/import-vcf-to-blackberry.html)|-|-|
Facebook|-|[Instructions here](https://www.contactually.com/blog/3-facebook-contacts-workarounds-to-give-you-control-of-your-network)|-|

# More resources.


* [Slide show I made on this topic](https://slides.com/alexesc/vcf)
* [Wikipedia article](https://en.wikipedia.org/wiki/VCard)
* [More info on how to make V-cards](https://archive.li/tZGj4#selection-441.10-441.20)