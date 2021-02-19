# DAQ-EXP_TA
Gumpf for TA

# LabVIEW instillation guide

> Contents
> - [VPN Install]{https://github.com/Nuclearpolo/DAQ-EXP_TA#1-so-for-my-vpn-gang-bang-in-university-of-manchester-it-into-your-search-engine-of-choice}
> - [Labview Install]{https://github.com/Nuclearpolo/DAQ-EXP_TA#7-once-thats-all-dandy-head-on-back-to-our-ai-overlord-google-and-slam-in-a-request-for-labview-2020-student-hit-the-top-link-you-will-need-to-login-at-somepoint-here-or-make-an-account-make-it-with-your-student-account-its-not-a-big-deal-but-it-just-saves-faff-if-it-turns-out-to-be-a-big-deal-you-know-how-fiddly-computers-can-be}
> - [Serial Number (Possibly fucked, see known issues)]{https://github.com/Nuclearpolo/DAQ-EXP_TA#known-issues}
> - [Know Issues]{https://github.com/Nuclearpolo/DAQ-EXP_TA#known-issues}
> - [Remote Access Resources]{https://github.com/Nuclearpolo/DAQ-EXP_TA/blob/main/README.md#remote-access}

Hi.
Labview has been abit of 
a pain so I've put together this 
guide to go with the video I will 
do later. 

> If you are finding trouble with the local install, the bottom of this guide now features a guide of how to remotely access a PC in George Begg or other. You can use labview there. 

First thing that needs doing is 
smashing open a google window. I 
am using firefox here but I doubt there will 
be any issues with other browsers.
We are going to do this the long way so 
you can get to the VPN if you need to. Traditional installs would require the vpn to access the licensing page to get the serial number, but I've been naughty and put that at the end.  
If you'd rather skip the vpn part and go 
straight to 7, you can follow that through to install.
It's cool, I understand. 

## NOTE: Known issues I'm still trying to figure out are at the bottom. If you suffer these, please post in the discussion forum.
## NOTE: It was pointed out by a fellow TA that it may be an issues with using the 64-Bit, as the instillation guide on the IT website explicitly states 32-bit.

## 1. So for my VPN gang, bang in "University of Manchester IT" into your search engine of choice.


![](2021-02-09-15-58-14.png)

## 2. Then hit the software link.

![](2021-02-09-15-58-45.png)

## 3. On this screen hit the software centre link.

![](2021-02-09-15-59-10.png)

## 4. If you don't get the welcome page as in (5), hit the home button it the top left.

![](2021-02-09-15-59-45.png)

## 5. On the welcome page type "Labview" and click the third suggestion "Labview: Installation"

![](2021-02-09-16-00-15.png)

## 6. This is where you can get the Globalprotect VPN. Some people have reported connection issues despite stable connections and I suspect this may help. If not, try to find some tasty Eduroam nearby. On the globalvpn page run through the steps as necessary. You'll need to grab DUO mobile, the 2 factor authentication app. It's used to log into the email so a lot of you might already have it. Bop in the student creds and install the vpn. 

![](2021-02-09-16-00-53.png)

## 6.1 When I installed the VPN, it shouted at me saying I was running processes it needed dead. Those are given an ID and can be found in the "services" section of "Task Manager" on windows. I don't own a MAC but I imagine its similar, I own linux but I can't remember how it works on there. 

![](2021-02-09-16-15-18.png)

## 6.2 The VPN is turned on up here, in the taskbar drop down menu. It's really nice and clear \s. Looks like a cute little globe, N'aw.

![](2021-02-09-16-37-04.png)

## 7. Once that's all dandy, head on back to our AI overlord google and slam in a request for "Labview 2020 student". Hit the top link. You will need to login at somepoint here, or make an account. MAKE IT WITH YOUR STUDENT ACCOUNT. Its not a big deal but it just saves faff if it turns out _to be_ a big deal, you know how fiddly computers can be.

![](2021-02-09-16-01-46.png)

## 7. I managed to install the 2020 version, however people have reported issues. My recommendation is to grab 2020 first, and resort to 2019 if it throws a fit. The activation code as far as I can tell works for both.

![](2021-02-09-16-02-26.png)

## 7.1 Choose the bit of your machine and hit download. 

![](2021-02-09-16-02-45.png)

## 8. Launch the exe that you are bestowed and give it access to permissions.

![](2021-02-09-16-03-18.png)

## 8. The NI package manager should boot and look like this. Here you need to select which things to install. The IT page has a few listed but they're not all on this list. In the 3 screenshots after this, I have shown all the various modules that worked for the serial code and those that didn't, don't waste time downloading those that don't work. You'll notice a lot of the options are greyed out in this screenshot, this is because I already have them installed.

![](2021-02-09-16-19-28.png)

## 8.1 Those that worked (Apologies for the backdated versions, been using LV a while):

![](2021-02-09-15-50-26.png)

![](2021-02-09-15-51-25.png)

![](2021-02-09-15-52-02.png)

## 9. Once you have checked all the boxes and hit next, it will recommend a bunch of stuff to install. *I recommend* ignoring such advice and unticking. If you find you are missing something later, boot the package installer and download it then.

![](2021-02-09-16-28-49.png)

## 10. Wait 1.23 Decieons for the software to install. Enjoy staring at those green squares. Oscillating around and around, perpetually. I'm pretty convinced after having these squares in my peripheral vision all day that I am either their slave or have witnessed the fundamental physics of our universe. 

![](2021-02-09-16-27-52.png) ![](2021-02-09-16-30-02.png) ![](2021-02-09-16-27-52.png) ![](2021-02-09-16-30-02.png)

## 11. Once that's done, you'll be presented with the product activation menu. Drop down the box and select "Enter a serial number".

![](2021-02-09-16-30-50.png)

## 12. This is the serial number: 
# **M85X11748**
## Bang that in every box and hit the activate button next to the dropdown menu.

![](2021-02-09-16-31-45.png)

## 13. With the universes favour, you will be granted your wish: a fresh and shiny new Labview install to suffer on for this unit, you're welcome. I hope this helped people out and you all got it working. If you have issues, I'm keeping an eye on the discussion board to feel free to post and we can see what's what. Big Love and see you all in the labs!

# Known Issues 

## The serial number is invalid even on those ticked in 8.1. NI says this may be a licensing file. If you want to play with that, go ahead, requires contacting them apparently, though I will try see what I can find. Update: Fault report has gone to IT. I will keep this updated with what comes back. Update: We have delegated this issue to IT. As yet no reply. If you find this issue I recommend accessing a pc in uni with the citrix method below

![](2021-02-10-21-50-24.png)

# Remote Access 

For some local downloads are being a pain. I feel sympathy, nothing worse than software buggering up for no reason. What can be don e as a workaround is tuning into a pc in uni via citrix. I've put the resources here:

- [Citrix login]{https://manchester.cloud.com/Citrix/StoreWeb/#/login}
- [Download Link from IT]{documents.manchester.ac.uk/display.aspx?DocID=51611}

Hope this helps guys. 
