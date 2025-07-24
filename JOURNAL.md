---
title: "modular-console"
author: "pizzalover125"
description: "A console that is 100% modular."
created_at: "2024-05-14"
---
Time Spent: 45 hours

### 5/14
I have had this idea for a while, but never got around to do it. Now is the perfect time! My plan is to make a basic cyberdeck with the Latte Panda Mu. I did a lot of research about how I will actually accomplish this. I found https://cyberdeck.cafe/build, and will follow some of that advice. I'll begin with looking at the full carrier board made by Latte Panda and try to understand how it works. Then I'll build a custom carrier board with the items of my choice. 
Time Spent: 2 hour

### 5/16
Sadly, this project must come to an end, mainly due to costs and tariffs. I'll probably pursue this without the help of Hack Club at a later date.
Time Spent: 1 hour.

### 5/18
SIKE!!! Got you there, didn't I. Ok in all seriousness, I'll still try to build this. Today, I just did a bunch of research on how to bring the cost down. At the end, I came up with these two things (majority of cost): 
Time Spent: 1 hour
<img src="https://hc-cdn.hel1.your-objectstorage.com/s/v3/22a4f3517c3c409dfcb84ba56c2d5779b66fb30e_image.png" />

### 5/21
I did a LOT more research. I never expected that this type of project would require this many hours of research. I'll stick with the MakerFocus battery and circuit. I unfortunately couldn't find an CAD file for that board that works, which is not ideal. I also want to go with the Waveshare 7 inch screen as it will offer better battery efficiency. So I'll have to end up designing a USB hub, a keyboard, and an enclosure for this project.
Time Spent: 2 hour
<img src="https://hc-cdn.hel1.your-objectstorage.com/s/v3/199d225ae9521473f7e80342e7a49ff868c6119a_screenshot_2025-05-21_at_4.29.33___pm.png" />

### 6/8
Okay time to revamp this project. I was originally wanting to make an ultra version of the Sprig. I decided to make it modular because thats just cool. I couldn't do much work because it was quite late at night. So... I just made a mockup in ExcaliDraw! Here it is:
Time Spent: 3 hours
XXXXX

### 6/19
I literally worked on this project the entire project today... First, I did some research. It was actually super easy to do. I'm using these small speakers that @alexren recommended. To power these, I also got two MAX98735A speaker drivers. It was at this moment I decided to make this project as cheap as possible. This is why I did not create any PCBs and used cheap modules instead. Then I found this cheap USB hub breakout on Adafruit's website, so I decided to go with it. I also found these ultra cheap USB-A breakouts on Amazon for less than a buck a pop. Finally, for this ultra cheap version, I'll use the Raspberry Pi 02w. Then I made the CAD. It was actually super hard as I'm pretty bad at CAD. It was a matter of finding the 3D models online, importing them, positioning them, and then creating mounting holes. This took a SUPER long time. Finally I got this: 
XXXXX

After that, I decided to reposition everything to be able to fit the Raspberry Pi 5. I kind of got the hang of it and was far faster. I also couldn't find a 3d model of the display driver, so I had to make my own. Here is what I got:
Time Spent: 10 hours
XXXXX

### 6/10
Today, I did not get much progress done. I was trying to figure out the best way to get audio. Turns out my janky solution from before was just too impractical. I researched and researched but got nothing. Then someone told me I could just use a TRRS USB to audio converter... that helps a lot! However, I haven't decided how I'm going to route the actual module yet. I, for some reason, decided to route wires instead:
Time Spent: 9 hours
XXXXX

### 6/11
Today was also a slow day. I decided to start making the modules. But turns out that the Waveshare RP2040-1s don't have KiCad files. I tried converting EasyEDA files to KiCad, but it did not output THT. So... I just have to use EasyEDA 😭. Its super hard to use and I just strongly dislike it. Howver, desperate times call for desperate measures. I gotted this draft of a schematic:
Time Spent: 8 hours
XXXXX

### 6/12
I finished the joycon modules today. But for some reason exporting to 3d in EasyEDA Std is terrible. So I had to migrate my project to PRO. However, when I exported, all the dimensions were wrong for some reason... so I'll just have to do what it outputted. Hopefully nothing goes wrong in production. Here are the right and left joycons:
XXXXX

I also made the schematic for the bottom keyboard / trackpad combo. Having enough space will be next to impossible, so I will have to make it wider most likely.
XXXXX
Time Spent: 7 hours

^^^ Notice the X's? I was supposed to put screenshots there but I accidentally deleted them all 😢

### 6/29
Today, I wrapped up the project. omg its been soooooooooooooooooooo long. I've put in so much effort, so its nice to see it paid off. I was working on this project AFK at this national speech and debate tournament, so I didn't journal those days. Here is an interesting view of the product: <br>
![image](https://github.com/user-attachments/assets/f6e088b9-3a73-42fb-8f9c-a02af9a43c91) <br>
Time Spent: 2 hours

