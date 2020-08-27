# GSoC2020
This repository provides a discription as well as links and pictures of my work during Google Summer of Code 2020. 

# My work
Basically, I developed new embroidery designs and implemented them by using the Catrobat programming language, more specifically the Pocket Code respectively the Embroidery Designer App. I exhibited what embroidery designs are feasible to create with the Catrobat visual programming language. Additionally I worked on an algorithm to fill polygons.

Furthermore, I have dealt with the possibilities of integrating electronics, i.e. LEDs or microchips, into an embroidery design.

Some parts of my work i documented on the Catrobat Wiki Page in the form of tutorials or information pages.

# Coded Embroidery Projects

Cat
https://share.catrob.at/app/project/af1e5ea7-e827-11ea-9251-005056a36f47

Leuchtkäfer (german)
https://share.catrob.at/app/project/8d6d24f7-e82e-11ea-9251-005056a36f47

Olaf
https://share.catrob.at/app/project/cb9c0fe4-e82d-11ea-9251-005056a36f47

Blossom
https://share.catrob.at/app/project/3e58e5b6-e82c-11ea-9251-005056a36f47

Melone (german)
https://share.catrob.at/app/project/d5b89acb-e82b-11ea-9251-005056a36f47

Butterflies
https://share.catrob.at/app/project/7bc2fd2c-e82b-11ea-9251-005056a36f47

Rainbow
https://share.catrob.at/app/project/0a40da3a-e82a-11ea-9251-005056a36f47

Biene (german)
https://share.catrob.at/app/project/155cd64f-e829-11ea-9251-005056a36f47

Maker Days Roboter (german)
https://share.catrob.at/app/project/a2b7433c-e82b-11ea-9251-005056a36f47

Violin clef
https://share.catrob.at/app/project/00e4cb4f-e828-11ea-9251-005056a36f47

Little Bird
https://share.catrob.at/app/project/c12d099f-e827-11ea-9251-005056a36f47

Rudolf
https://share.catrob.at/app/project/b648c1a2-e79e-11ea-9251-005056a36f47

Paperplane
https://share.catrob.at/app/project/110cd10d-e79d-11ea-9251-005056a36f47

Panda
https://share.catrob.at/app/project/6a88266e-e79c-11ea-9251-005056a36f47

Horse
https://share.catrob.at/app/project/931ab8cc-e79b-11ea-9251-005056a36f47

Dog
https://share.catrob.at/app/project/5d061b93-e79b-11ea-9251-005056a36f47

Pineapple
https://share.catrob.at/app/project/70862d02-e79a-11ea-9251-005056a36f47

dumbbell
https://share.catrob.at/app/project/ae72472d-e799-11ea-9251-005056a36f47

Skye (in progress)

Yoshi (in progress)




These projects include algorithms for special stitches like a grid stitch, which are implemented by just using the stitch brick instead of preprogrammed stitches:

stitches
https://share.catrob.at/app/project/7e6b2636-e828-11ea-9251-005056a36f47

Unterwasserwelt (german)
https://share.catrob.at/app/project/b3c5e9a2-e82e-11ea-9251-005056a36f47

10101 stitch
https://share.catrob.at/app/project/7b06013b-e82e-11ea-9251-005056a36f47

Cupcake (german)
https://share.catrob.at/app/project/d05b5da2-e82a-11ea-9251-005056a36f47

Strawberry
https://share.catrob.at/app/project/9cc13f82-e827-11ea-9251-005056a36f47

Trunk
https://share.catrob.at/app/project/d02e19d7-e827-11ea-9251-005056a36f47




These projects include the tatami fill stitch algorithm to fill some areas in the design:

Bird
https://share.catrob.at/app/project/29be3ef8-e82e-11ea-9251-005056a36f47

Logo TU Graz
https://share.catrob.at/app/project/7f539d63-e82c-11ea-9251-005056a36f47

Loewe (german)
https://share.catrob.at/app/project/8c1334b4-e82a-11ea-9251-005056a36f47



# Work with electronics in combination with embroidery

 On the Catrobat wiki page https://wiki.catrobat.org/bin/view/Education/Embroidery/Special%20Embroidery%20Designs%3A%20Electronics%20to%20shine/ I have documented how to sew LEDs and a coin cell battery onto a design.

Another goal would have been to be able to control the LEDs, which are built into the design, with a microchip. This worked with the Arduino UNO in combination with the Bluetooth module HC-05, but the problem was that this hardware, especially the Arduino UNO, is not sewable. Modern sewable Bluetooth modules all work with Bluetooth Low Energy, but the Embroidery Designer does not support this type of Bluetooth -> Solution: make Embroidery Designer compatible (high effort) or use an old Bluetooth module.

So, I tried to connect the HC-05 Bluetooth module with the Microchips Circuit Playground Classic and Lilypad 328 Main Board. Because the so-called "Old Standard Firmata" has to be used to control the Bluetooth module via the Embroidery Designer/Pocket Code, I loaded it onto the respective microchips. An explenation why this does not work would be work in progress.

# Catrobat Wiki pages I created

https://wiki.catrobat.org/bin/view/Education/CodedEmbroidery/?language=en

https://wiki.catrobat.org/bin/view/Education/Embroidery/Special%20Embroidery%20Designs%3A%20Electronics%20to%20shine/

https://wiki.catrobat.org/bin/view/Education/Embroidery/Introduction%20To%20The%20World%20Of%20Embroidery/


Additionally, I created each page in german too as well as many tutorial pages additional tutorialpages on this page https://wiki.catrobat.org/bin/view/Education/Embroidery/?language=en. 

# Work in progress

As I have got some hours left, I will create more Embroidery projects as well as a new wiki page, where I will provide a lesson plan for teachers. I will improve the algorithm to automatically fill polygons so that the algorithm will be easy to use for everybody.
