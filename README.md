# Playstation plus on linux
This is a working set of instructions to run the Playstation Plus launcher on linux via lutris
![image](https://user-images.githubusercontent.com/106441310/190964432-62f9f1ae-21c8-46bb-832e-98d4bd1c0b79.png)<!--intro image-->

# What is Playstation Plus?
Playstation Plus is a sony subscription service that allows you to stream Playstation 3/4/5 games to your windows pc. It also gives you access to online play and cloud storage, etc. To use Playstaion Plus for game streaming you do need a sony account and to have paid for either the PS Plus extra or the PS Plus Premium plans. This will not work if you don't have either of those. Also do not get the essentials plan as it does not include game streaming as an option. [See sony's website](https://www.playstation.com/en-us/ps-plus/#subscriptions) for more details on a ps plus plan.
![image](https://user-images.githubusercontent.com/106441310/190967292-ba602b2d-2e74-487c-bc28-5d2a39738701.png)<!--membership-->


# Getting started
After making a sony account or loggin in, it might be a little unclear where to go after you purchase PS plus, sometimes thier site will redirect you to a download for PS plus's .exe and sometimes it doesn't. If you need the PS Plus.exe you can get it [here](https://download-psplus.playstation.com/downloads/psplus/pc/latest)
Next you're going to need a peice of software called Lutris. Lutris is a manager for your games/proton/wine versions. If you are unfamiliar with wine or proton, those are compatibility layers that allow .exe files or windows programs to run on linux, it's a pretty good tool to use but it's not perfect. Everything on wine or proton requires some form of tweaking if it doesn't work, And that's why it's important if you want PS Plus to run that you set this up exactly how I do. Don't worry it's not hard lol. You can find a link to Lutris [here](https://lutris.net/downloads) make sure you get the version meant for your distro.

# Installing PS Plus on Lutris
Upon running Lutris for the first time you will be welcomed by a window similar to what you see in my image below. Again this can manage a ton of games including steam and epic as well as ubisoft, but let's not get off track. First thing you're gonna wanna do is to go to the sidebar on the left and click on wine if you don't already have that selected.
![image](https://user-images.githubusercontent.com/106441310/190971109-778e2fda-b9ad-47ab-b04e-b07b16b250ee.png)<!--lutris menu-->

# Installing Wine
Next click on the little icon left of the settings cog and install "Lutris-7.2-2. This is the best version of wine that iv'e gotten PS Plus to run with, it shouldn't crash or have any issues. If you do encounter any issues please let me know. Go ahead and close out of that menu after wine is done installing.

![image](https://user-images.githubusercontent.com/106441310/190971973-828f3a77-c757-4665-81ea-69b71b6a78c1.png)<!--wine versions-->

# Adding PS Plus to Lutris
Next go ahead and click on the plus button on the top left of Lutris, it will open the add game menu, click add locally installed game.
![image](https://user-images.githubusercontent.com/106441310/190972132-3a0326f1-ebaf-475e-ae3e-47a165010e71.png)<!--add game-->

# Basic info
Next we are going to give lutris all the info and settings PS Plus needs. In the name field type in a name of your choice that you want the game to appear as in your main menu, mine is "ps plus". Then open the runner drop down menu and select wine.
![image](https://user-images.githubusercontent.com/106441310/190972487-5c7cb1ff-2d69-4b4e-b3ce-1d5bdab57abf.png)<!--game info-->

# Setting the path
Next navigate to the Game options tab, and click browse on the executable section. From there navigate to where you downloaded your PS Plus setup.exe and select it![image](https://user-images.githubusercontent.com/106441310/190974502-c47d1c98-ef29-423c-a690-6e39bc98f754.png)<!--game directory-->

# Runner options
Now go into the Runner options tab and toggle show advanced options at the bottom left, then make sure all your settings in this tab match mine.
![image](https://user-images.githubusercontent.com/106441310/190975098-0766af26-1b3f-4ee9-9d9c-ac7aa905bec8.png)<!--runner options 1-->
![image](https://user-images.githubusercontent.com/106441310/190975171-edfa09e8-9ad9-4123-8feb-47cab84011cd.png)<!--runner options 2-->

# System options
Now onto the last tab which is System options, once you're in there make sure you toggle "Disable Lutris Runtime" (to avoid any confusion you want it to be blue with a checkmark) if that's left off then ps plus will not work with Playstation/direct-input controllers, and you also will have no sound in game. So if you have either of those issues please ensure this setting is on. Along with that make sure the rest of these settings match mine with the exception of your home directory of course, it should look like mine but with your name.![image](https://user-images.githubusercontent.com/106441310/190975538-f37d1b97-79aa-4cb8-bd15-0b4b0447c8ba.png)<!--system options-->
![image](https://user-images.githubusercontent.com/106441310/190975582-3b61f3ee-3f28-4a94-9ed6-a4c41261070d.png)<!--system options 2-->

# Save your settings
Lastly hit save, you're all done configuring!


![image](https://user-images.githubusercontent.com/106441310/190987240-c2aa9fb8-a38a-480e-a3b3-9b7fe48ebd0f.png)


# Running PS Plus the first time
Now all you gotta do is run ps plus from lutris and the first time you do it, you will be greeted with the Playstation Plus installer.
![image](https://user-images.githubusercontent.com/106441310/190975805-a96b668f-f0f6-415a-b0c7-801aa1b243ed.png)<!--menu with ps plus-->



# Installation
Go ahead and hit Next to install it, no need to mess with any directory settings because it's important that wine installs this to your virtual c drive that it creates for your windows applications/.exe's.
![image](https://user-images.githubusercontent.com/106441310/190975906-5072b29d-e207-420c-9001-5646d5339788.png)<!--psplus setup-->


# Completing the setup
Once it's finished installing PS Plus click finish, if PS Plus doesn't launch you can launch it from Lutris, and tha'ts how you'll launch it from  now on unless you make a shortcut to it or pin it to a taskbar.
![image](https://user-images.githubusercontent.com/106441310/190977062-92b5aa12-4485-4094-bc4a-d7588f670471.png)<!--psplus setup finish-->

# DOWNLOADING MSVCR120.DLL
One thing needed for ps plus to work on linux properly is to donwload "MSVCR120.DLL" I found this out by doing some research on the origional PS Now sony had a long time ago which is a predecessor to PS Plus, this file is needed for it to run on anything other than windows.You can download [MSVCR120.DLL](here)

# Placing MSVCR120.DLL in PS Plus

![image](https://user-images.githubusercontent.com/106441310/190990254-2814a40a-aef5-464b-b4a1-cb229b91450f.png)

# Starting PS Plus
Everytime you launch it you're going to see the ps plus logo and a warning sayinng ps plus may not function correctly in a virtual machine, this is not a virtual machine, this is a compatibility tool so im unsure what makes it give this warning or how to disbale it just yet,just click ok and ps plus will open just as it would on windows.


![image](https://user-images.githubusercontent.com/106441310/190988133-c9ded000-18fc-4f42-ad4f-02a21ff899e6.png)


# Sign in and sign in issues
Now just sign into PS Plus with your sony account and you should be good to go! Don't be dischouraged if the sign in doesn't work the first time, iv'e tested this on both windows and linux and at the moment sony has left it in a bit of a buggy state as it took me 3 attempts to sign in and actually load into the menu properly.
![image](https://user-images.githubusercontent.com/106441310/190978484-cabd6485-b8fe-4aaf-890b-e95d3638c696.png)<!--psplus logo-->


PS Plus games also will not launch unless you have a controller connected, so make you you've got one hooked up, and then click on the tv icon at the top right to switch to controller mode. Happy streaming!


![image](https://user-images.githubusercontent.com/106441310/190978737-94ab5305-26df-4a1f-9932-aa19302fbf23.png)<!--psplus controller mode-->






















