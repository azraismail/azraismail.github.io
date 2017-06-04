---
title: "PaparazziBot"
layout: post
date: 2016-12-12
# tag: jekyll
# image: /assets/images/jekyll-logo-light-solid.png
headerImage: true
projects: true
coursework: false
research: false
awards: false
hidden: true # don't count this post in blog pagination
description: "A bot that can look for a face in the crowd and can be controlled remotely."
author: azra-ismail
externalLink: false

---

For a class design project (ECE 4180 - embedded systems design), my team built an mbed bot paired with a Raspberry Pi 3 that could scan for a face in a crowd. Input could be provided by the user through a C# application that communicates with the Raspberry Pi over WiFi. A user could provide directions for the bot to move in, provide the name for a person to scan a crowd for in auto mode, and also just take a picture and analyze its contents. We use the IBM Watson API to build an application in node-red that runs on the Raspberry Pi. The app determines who is present in an image and then posts the result on a twitter page - https://twitter.com/ece4180Group. Communication between the Raspberry Pi and the mbed is done via serial.

Currently the IBM computer vision software can only detect celebrities, hence the term - paparazziBot. Ideally, one could train the model on any face, and by giving it pictures of criminals, it could function as a security bot.

#### Tags

- ARM mbed
- Raspberry Pi
- camera
- motors
- WiFi/Serial

---
[Check it out](https://developer.mbed.org/users/azndevil/notebook/paparazzi-bot/) If you need some help, just [tell me](http://github.com/aismail1997/aismail1997.github.io/issues).
