[![Telegram](https://img.shields.io/badge/join-telegram-blue.svg?style=for-the-badge)](https://t.me/+W4rVVa0_VLEzYmI0)
 [![WhatsApp](https://img.shields.io/badge/join-whatsapp-green.svg?style=for-the-badge)](https://chat.whatsapp.com/FkNC7u83kuy2QRA5sqjBVg) 
 [![Donate](https://img.shields.io/badge/donate-$-brown.svg?style=for-the-badge)](http://paypal.me/mtpsilva)
 [![Say Thanks](https://img.shields.io/badge/Say%20Thanks-!-yellow.svg?style=for-the-badge)](https://saythanks.io/to/mtpsilva)
![](https://img.shields.io/github/last-commit/aeonSolutions/AeonLabs-AI-Volvo-MKII-Open-Hardware?style=for-the-badge)
<a href="https://trackgit.com">
<img src="https://us-central1-trackgit-analytics.cloudfunctions.net/token/ping/l5m5z1845s10s47cuyl5" alt="trackgit-views" />
</a>
![](https://views.whatilearened.today/views/github/aeonSolutions/AeonLabs-AI-Volvo-MKII-Open-Hardware.svg)
[![Open Source Love svg1](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](#)
[![GitHub Forks](https://img.shields.io/github/forks/aeonSolutions/AeonLabs-AI-Volvo-MKII-Open-Hardware.svg?style=social&label=Fork&maxAge=2592000)](https://www.github.com/aeonSolutions/AeonLabs-AI-Volvo-MKII-Open-Hardware/fork)
[![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat&label=Contributions&colorA=red&colorB=black	)](#)
[<img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" data-canonical-src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" height="30" />](https://www.buymeacoffee.com/migueltomas)

<p align="center">
   <img src="https://github.com/aeonSolutions/AeonLabs-AI-Volvo-MKII-Open-Hardware/blob/main/media/volvo_mk2_banner.png" height="300">
</p>

[PCB-Prototyping-Catalogue](https://github.com/aeonSolutions/PCB-Prototyping-Catalogue)  >>  [Vehicle Automation](https://github.com/aeonSolutions/PCB-Prototyping-Catalogue/tree/main/Vehicle%20Automation)  >> Volvo MKII Open Hardware

# Volvo MKII Open Hardware

What's planned for 2024.... <br>
The electrical system and electronics for all Volvo's with the common chassis MKII, period 1998 to 2005, using the existing wiring on those cars (backward compatible) and replacing all electronics with open hardware I will design and prototype. To achieve this task I will be using donor car electronics and electrical wiring I already have. This will serve as a ground base to commercialize automotive solutions using an open business logic (open hardware and open software) for other car brands and models. Including LPG systems.

**The problem** <br>
Nowadays, repairing hardware electronics is impossible or almost impossible. Current practice forces a car owner to replace instead of repair. This has a really high cost and pushes owners to seek other less trustworthy solutions using used components from other vehicles. Since this type of components is nowadays heavily protected, maintenance and repair outside the official car manufacturer authorized dealer poses additional risks every time a piece of hardware electronics or firmware requires reverse engineering and modification just to enable it and make it work in another vehicle.

**The Ideia** <br>
Design and prototype OEM hardware electronics capable to the same operation and functionality, however instead of using closed and protected logic, it uses open hardware and open firmware hardware electronics as a direct replacement into existing* wiring in a vehicle, in particular older cars. This will facilitate repeatability and maintenance on any "repair shop" outside authorized dealers. And requires no reverse engineering and no modification to make it work in a vehicle.<br>

Since this is an open hardware project, the main selection of choice for the operating system will be Android Auto for the main LCD screen , in the center console. Nowadays there are a plenitude of "open auto" solutions using a raspberry pi. I'll be designing the hardware electronics made to fit an SoC module, and i'll be starting with NVidia's Jetson Nano. In the following YouTube video there's a good example of a traditional media unit https://www.youtube.com/watch?v=RgbHXTHUnQw

<br>

**What hardware electronics will be conceptualized , prototyped and tested** <br>
**1st Milestone** <br>
The first milestrone has the main objective to do a direct replacement of all proprietary hardware electronics and replace them by open hardware solutions i'll be prototyping, namely: 
- The ECU, in all similar to the one sold by the Austrians [HalTech](https://www.haltech.com) and the well known Speedduino.
- The ETM throtle control
- The instrument cluster on the dashboard
- The Air Quality Control module
- The Car Media Audio
- The Door locking for each door plus the trunk
- The control electronics for the front headlights , i'll b adding a "cargo load" sensor to automaticaly adjust the headlight beam angle
- The control electronics for the back headlights

**2nd Milestone** <br>
In second milestone i'll be replacing the factory Air Quality control unit and also the Car Audio in the center console by a custom made LCD screen, in particular:
- Add an LCD screen to the center console running Android Auto with software customizations

**3rd Milestone** <br>
In the third milestone I'll be replacing the factory instrument cluster dashboard unit and replace it with a custom made LCD screen for some cool 3D graphics rending , in particular:
- add an LCD screen to the instrument cluster running some cool 3D graphics rendering
- make it compatible for autonomous driving modules

**4th Milestone** <br>
In the fourth milestone I'll be adding Autonoous driving capabilities ...
- Obstacle detection and automatic breaking

<p align="center">
   <img src="https://github.com/aeonSolutions/AeonLabs-AI-Volvo-MKII-Open-Hardware/blob/main/media/VOLVO%20XC60%20XC90%20FRONT%20COLLISION%20WARNING%20CAMERA%2032209885.jpg" height="200">
</p>

- Direct compatible with [Comma.ai](http://www.comma.ai) autonomous driving solution (open hw & sw)

<p align="center">
   <img src="https://github.com/aeonSolutions/AeonLabs-AI-Volvo-MKII-Open-Hardware/blob/main/media/Comma.ai-3X-front-shop-1680x1260.jpg" height="200">
</p>

<br>
<br>

## WIKI
Go to the [wiki page](https://github.com/aeonSolutions/AeonLabs-AI-Volvo-MKII-Open-Hardware/wiki) to learn more.

<br>

## Compatibility

<p align="center">
 <a href"https://www.apple.com/ios/carplay/">
<img src="https://github.com/aeonSolutions/AeonLabs-AI-Volvo-MKII-Open-Hardware/blob/main/media/AppleCarPlay-Logo.jpg" height="50">
 </a>
<a href="https://www.android.com/intl/en_be/auto/"> 
 <img src="https://github.com/aeonSolutions/AeonLabs-AI-Volvo-MKII-Open-Hardware/blob/main/media/android_auto_logo.jpg" height="50">
 </a>

<a href="https://csa-iot.org/all-solutions/matter/">  
 <img src="https://github.com/aeonSolutions/PCB-Prototyping-Catalogue/blob/main/media/works_with_matter.png" height="50">
 </a>
<a href="https://csa-iot.org/all-solutions/matter/">  
 <img src="https://github.com/aeonSolutions/PCB-Prototyping-Catalogue/blob/main/media/works_with_zigbee.jpg" height="50">
 </a>
</p>

<br>

## What one additionally needs
- [USB to UART/USB TTL firmware burner for 5V and 3.3V MCUs ](https://github.com/aeonSolutions/PCB-Prototyping-Catalogue/blob/main/DIY-Maker/README.md)
- [Upgradable ESP32 MCU](https://github.com/aeonSolutions/AeonLabs-Upgradable-MCU-ESP32)
  
<br />
<br />

**Get a Notification on every PCB update**

| [<img src="https://github.com/aeonSolutions/PCB-Prototyping-Catalogue/blob/main/mailing-list_orig.png" alt="" width="80">](https://www.tindie.com/stores/aeonlabs/) | You can fill in your [email here (Google form)](https://docs.google.com/forms/d/e/1FAIpQLScErMgQYRdA-umvCjvTPPrCO7Lg1QYowTxb7vfa8cTfrcPEAA/viewform?usp=pp_url) and I'll send a reminder when a new PCB prototype is made available here or a new revision for an existing PCB. Stay tuned! |
|-------------|------|

<br>
<br>

## Author

You can get in touch with me on my LinkedIn Profile:

#### Miguel Tomas

[![LinkedIn Link](https://img.shields.io/badge/Connect-Miguel--Tomas-blue.svg?logo=linkedin&longCache=true&style=social&label=Connect)](https://www.linkedin.com/in/migueltomas/)

You can also follow my GitHub Profile to stay updated about my latest projects: [![GitHub Follow](https://img.shields.io/badge/Connect-Miguel--Tomas-blue.svg?logo=Github&longCache=true&style=social&label=Follow)](https://github.com/aeonSolutions)

<br>

### Be supportive of my dedication and work towards technology education and buy me a cup of coffee
The PCB Desgin Files i provide here for anyone to use are free. If you like this Smart Device or use it, please consider buying me a cup of coffee, a slice of pizza or a book to help me study, eat and think new PCB design files.

[<img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" data-canonical-src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" height="50" />](https://www.buymeacoffee.com/migueltomas)

<br />

### Make a donation on Paypal
Make a donation on paypal and get a TAX refund*.

[![](https://github.com/aeonSolutions/PCB-Prototyping-Catalogue/blob/main/media/paypal_small.png)](http://paypal.me/mtpsilva)

<br>

### Support all these open hardware projects and become a patreon  
Liked any of my PCB KiCad Designs? Help and Support my open work to all by becomming a LDAD Patreon.
In return I will give a free PCB design in KiCad to all patreon supporters. To learn more go to patreon.com. Link below.

[![](https://github.com/aeonSolutions/PCB-Prototyping-Catalogue/blob/main/media/patreon_small.png)](https://www.patreon.com/ldad)

<br />
<br />

______________________________________________________________________________________________________________________________
### License

Before proceeding to download any of AeonLabs software solutions for open-source development and/or PCB hardware electronics development make sure you are choosing the right license for your project. See [AeonLabs Solutions for Open Hardware & Source Development](https://github.com/aeonSolutions/PCB-Prototyping-Catalogue/wiki/AeonLabs-Solutions-for-Open-Hardware-&-Source-Development) for more information. 
