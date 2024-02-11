[![Telegram](https://img.shields.io/badge/join-telegram-blue.svg?style=for-the-badge)](https://t.me/+W4rVVa0_VLEzYmI0)
 [![WhatsApp](https://img.shields.io/badge/join-whatsapp-green.svg?style=for-the-badge)](https://chat.whatsapp.com/FkNC7u83kuy2QRA5sqjBVg) 
 [![Donate](https://img.shields.io/badge/donate-$-brown.svg?style=for-the-badge)](http://paypal.me/mtpsilva)
 [![Say Thanks](https://img.shields.io/badge/Say%20Thanks-!-yellow.svg?style=for-the-badge)](https://saythanks.io/to/mtpsilva)
![](https://img.shields.io/github/last-commit/aeonSolutions/AeonLabs-AI-Volvo-MKII-Open-Hardware?style=for-the-badge)
<a href="https://trackgit.com">
<img src="https://us-central1-trackgit-analytics.cloudfunctions.net/token/ping/lpkxg8capf0t6hv9cqrl" alt="trackgit-views" />
</a>
![](https://views.whatilearened.today/views/github/aeonSolutions/AeonLabs-AI-Volvo-MKII-Open-Hardware.svg)
[![Open Source Love svg1](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](#)
[![GitHub Forks](https://img.shields.io/github/forks/aeonSolutions/AeonLabs-AI-Volvo-MKII-Open-Hardware.svg?style=social&label=Fork&maxAge=2592000)](https://www.github.com/aeonSolutions/AeonLabs-AI-Volvo-MKII-Open-Hardware/fork)
[![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat&label=Contributions&colorA=red&colorB=black	)](#)
[<img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" data-canonical-src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" height="30" />](https://www.buymeacoffee.com/migueltomas)
<a href="https://github.com/sponsors/aeonSolutions">
   <img height="40" src="https://github.com/aeonSolutions/PCB-Prototyping-Catalogue/blob/main/media/become_a_github_sponsor.png">
</a>

<p align="center">
   <img src="https://github.com/aeonSolutions/AeonLabs-AI-Volvo-MKII-Open-Hardware/blob/main/media/volvo_mk2_banner.png" height="100%">
</p>

[PCB-Prototyping-Catalogue](https://github.com/aeonSolutions/PCB-Prototyping-Catalogue)  >>  [Vehicle Automation](https://github.com/aeonSolutions/PCB-Prototyping-Catalogue/tree/main/Vehicle%20Automation)  >> Volvo P2 Open Hardware

<div align="right">
 <a href="https://github-com.translate.goog/aeonSolutions/AeonLabs-AI-Volvo-MKII-Open-Hardware/wiki?_x_tr_sl=en&_x_tr_tl=pt&_x_tr_hl=en&_x_tr_pto=wapp">Change language</a> <br>
 Last update: 6-2-2024
</div>

# Volvo P2 Open Hardware
[where to buy](https://github.com/aeonSolutions/PCB-Prototyping-Catalogue/wiki/Where-to-Buy) already assembled and ready to use.

**The problem** <br>
Nowadays, repairing hardware electronics is impossible or almost impossible. Current practice forces a car owner to replace instead of repair. This has a really high cost and pushes owners to seek other less trustworthy solutions using used components from other vehicles. Since this type of components is nowadays heavily protected, maintenance and repair outside the official car manufacturer authorized dealer poses additional risks every time a piece of hardware electronics or firmware requires reverse engineering and modification just to enable it and make it work in another vehicle.

**The Ideia** <br>
Design and prototype OEM hardware electronics for all Volvo's with the common chassis P2, period 1998 to 2009 (S80, S60, V70 XC70, XC90), using the existing wiring on those cars (backward compatible) to enable a direcct replacement of the existing factory hardware. Prototyped electronics are capable and have the same operation and functionality, however instead of using closed and protected logic, it uses open hardware and open firmware as a direct replacement into existing* wiring in a vehicle, in particular older cars. This will facilitate repeatability and maintenance on any "repair shop" outside authorized dealers. And requires no reverse engineering and no modification to make it work in a vehicle. To achieve this task I will be using donor car electronics and electrical wiring I already have. This will serve as a ground base to commercialize automotive solutions using an open business logic (open hardware and open software) for other car brands and models. Including LPG systems. <br>

<div align="center">

***"still.... even if it is not easily possible ...it will definitely going to be AWESOME running a car <br> that will meet the latest EURO emissions except on the pink slip"*** <br>
<sup> <a href="https://discordapp.com/channels/879495735912071269/937480820594208808/1203010918833721446">Discord Server of Speeduino 02-02-2024 </a> </sup>
</div>

Since this is an open hardware project, the main selection of choice for the operating system will be Android Auto for the main LCD screen , in the center console. Nowadays there are a plenitude of "open auto" solutions using a raspberry pi. I'll be designing the hardware electronics made to fit an SoC module, and i'll be starting with NVidia's Jetson Nano. In the following YouTube video there's a good example of a traditional media unit https://www.youtube.com/watch?v=RgbHXTHUnQw

<br>

## What hardware electronics will be conceptualized , prototyped and tested
The main objective of this project is to study the advantages of using open solutions an compare it with conventional hardware electronics solutions. In particular in regards to serviceability, maintenance and repairability and also important, in regards to personal ownership safety. While driving and while parked (thieves).

**1st Milestone** <br>
The first milestrone has the main objective to do a direct replacement of all proprietary hardware electronics and replace them with open hardware solutions i'll be prototyping, namely: 
- The [ECU](https://github.com/aeonSolutions/AeonLabs-AI-Volvo-MKII-Open-Hardware/wiki/ECU), in all similar to the one sold by the Austrians [HalTech](https://www.haltech.com) and the well known [Speeduino](https://speeduino.com/home/).
-  An [ECU Diagnostics]() , programming and Tunning Tablet device  
- The [ETM](https://github.com/aeonSolutions/AeonLabs-AI-Volvo-MKII-Open-Hardware/wiki/ETM) throttle control
- The [Airbags control module](https://github.com/aeonSolutions/AeonLabs-AI-Volvo-MKII-Open-Hardware/wiki/Airbags-control-module)
- The [Electronic Stability Control](https://github.com/aeonSolutions/AeonLabs-AI-Volvo-MKII-Open-Hardware/wiki/Electronic-Stability-Control)
- The [Instrument cluster](https://github.com/aeonSolutions/AeonLabs-AI-Volvo-MKII-Open-Hardware/wiki/Instruments-Cluster) on the dashboard
  - LED retro illumination Mod
    - [Fuel Gauge](https://github.com/aeonSolutions/AeonLabs-AI-Volvo-MKII-Open-Hardware/wiki/Fuel-Gauge-LED-retro-illumination)
    - [Temperature Gauge](https://github.com/aeonSolutions/AeonLabs-AI-Volvo-MKII-Open-Hardware/wiki/Temperature-Gauge-LED-retro-illumination)
    - [Engine RPM Gauge](https://github.com/aeonSolutions/AeonLabs-AI-Volvo-MKII-Open-Hardware/wiki/Engine-RPM-Gauge-LED-retro-illumination)
    - [Speed Gauge](https://github.com/aeonSolutions/AeonLabs-AI-Volvo-MKII-Open-Hardware/wiki/Speed-Gauge-LED-retro-illumination)
  - LED retro illumination with LCD TFT Color Display
    - [Engine RPM Gauge](https://github.com/aeonSolutions/AeonLabs-AI-Volvo-MKII-Open-Hardware/wiki/Engine-RPM-Gauge-LED-retro-illumination-with-LCD-TFT-Display)
    - [Speed RPM Gauge](https://github.com/aeonSolutions/AeonLabs-AI-Volvo-MKII-Open-Hardware/wiki/Speed-Gauge-LED-retro-illumination-with-LCD-TFT-Display)
- The [Climate Control module](https://github.com/aeonSolutions/AeonLabs-AI-Volvo-MKII-Open-Hardware/wiki/Climate-Control-Module)
- The [Car Media Audio](https://github.com/aeonSolutions/AeonLabs-AI-Volvo-MKII-Open-Hardware/wiki/Car-Media-Audio)
- The [Rear-view mirror](https://github.com/aeonSolutions/AeonLabs-AI-Volvo-MKII-Open-Hardware/wiki/Rear-View-Mirror)
- The [Door locking](https://github.com/aeonSolutions/AeonLabs-AI-Volvo-MKII-Open-Hardware/wiki/Door-Locking) for each door plus the trunk
    - [LED retro illumination Mod (back doors)](https://github.com/aeonSolutions/AeonLabs-AI-Volvo-MKII-Open-Hardware/wiki/LED-retro-illumination-Mod-(back-doors))
- The [Control electronics for the front headlights](https://github.com/aeonSolutions/AeonLabs-AI-Volvo-MKII-Open-Hardware/wiki/Front-headlights) , I'll b adding a "cargo load" sensor to automatically adjust the headlight beam angle
- The [Control electronics for the back lights](https://github.com/aeonSolutions/AeonLabs-AI-Volvo-MKII-Open-Hardware/wiki/Back-lights)

**2nd Milestone** <br>
In second milestone I'll be replacing the factory Air Quality control unit and also the Car Audio in the center console by a custom made LCD screen, in particular:
- Add an LCD screen to the center console running Android Auto with software customizations

**3rd Milestone** <br>
In the third milestone I'll be replacing the factory instrument cluster dashboard unit and replace it with a custom made LCD screen for some cool 3D graphics rending , in particular:
- add an LCD screen to the instrument cluster running some cool 3D graphics rendering
- make it compatible for autonomous driving modules

**4th Milestone** <br>
In the fourth milestone I'll be adding Autonoous driving capabilities ...
- Obstacle detection and automatic breaking
- Direct compatible with [Comma.ai](http://www.comma.ai) Autonomous driving solution (open hw & sw)


<br>
<br>

## WIKI
To continue reading about this project, go to the [wiki page](https://github.com/aeonSolutions/AeonLabs-AI-Volvo-MKII-Open-Hardware/wiki). Thank you.

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

**Get a Notification on every PCB update**

| [<img src="https://github.com/aeonSolutions/PCB-Prototyping-Catalogue/blob/main/mailing-list_orig.png" alt="" width="80">](https://www.tindie.com/stores/aeonlabs/) | You can fill in your [email here (Google form)](https://docs.google.com/forms/d/e/1FAIpQLScErMgQYRdA-umvCjvTPPrCO7Lg1QYowTxb7vfa8cTfrcPEAA/viewform?usp=pp_url) and I'll send a reminder when a new PCB prototype is made available here or a new revision for an existing PCB. Stay tuned! |
|-------------|------|

<br>

**Hire AeonLabs** <br>
If you like my work here and are looking to design and deploy your own smart device find [here](https://github.com/aeonSolutions/PCB-Prototyping-Catalogue/wiki/How-to-Hire-AeonLabs) how to hire me. 

<br>

## Join the Beta Program
Join the beta program to test and debug to provide feedback, ideas, modifications, suggestions, improvements. And in return, write your own article blog or post on social media about it. See participation conditions on the [Wiki](https://github.com/aeonSolutions/PCB-Prototyping-Catalogue/wiki/Beta-Participation-Agreement).  

## Contributing

Bug reports and pull requests are welcome on any of AeonLabs repositories. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [code of conduct](https://github.com/aeonSolutions/OpenScience-Dataverse-API-C-library/blob/main/CODE_OF_CONDUCT.md).

- Contributing
  - [Your Contributions Matter](https://github.com/aeonSolutions/PCB-Prototyping-Catalogue/wiki/Your-Contributions-Matter)
  - [Contributor Code of Conduct](https://github.com/aeonSolutions/PCB-Prototyping-Catalogue/wiki/Contributor-Code-of-Conduct)

<br>

**[Beta Participation Agreement](https://github.com/aeonSolutions/PCB-Prototyping-Catalogue/wiki/Beta-Participation-Agreement)**

The Beta Participant Agreement is a legal document being executed between you and AeonLabs that outlines the conditions when participating in the Beta Program.

## Coding standards

Please make sure tests pass before committing, and add new tests for new additions.

- Licensing 
  - [AeonLabs Solutions for Open Hardware & Source Development](https://github.com/aeonSolutions/PCB-Prototyping-Catalogue/wiki/AeonLabs-Solutions-for-Open-Hardware-&-Source-Development)

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

<p align="center">
    <a href="https://www.buymeacoffee.com/migueltomas">
        <img height="35" src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png">
    </a>
</p>


### Make a donation on Paypal
Make a donation on paypal and get a TAX refund*.

<p align="center">
    <a href="http://paypal.me/mtpsilva">
        <img height="35" src="https://github.com/aeonSolutions/PCB-Prototyping-Catalogue/blob/main/media/paypal_small.png">
    </a>
</p>

### Support all these open hardware projects and become a Github sponsor  
Liked any of my PCB KiCad Designs? Help and Support my open work to all by becomming a Github sponsor.

<p align="center">
    <a href="">
        <img height="50" src="https://github.com/aeonSolutions/PCB-Prototyping-Catalogue/blob/main/media/want_to_become_a_sponsor.png">
    </a>
    <a href="https://github.com/sponsors/aeonSolutions">
        <img height="50" src="https://github.com/aeonSolutions/PCB-Prototyping-Catalogue/blob/main/media/become_a_github_sponsor.png">
    </a>
</p>

# 

### License

Before proceeding to download any of AeonLabs software solutions for open-source development and/or PCB hardware electronics development make sure you are choosing the right license for your project. See [AeonLabs Solutions for Open Hardware & Source Development](https://github.com/aeonSolutions/PCB-Prototyping-Catalogue/wiki/AeonLabs-Solutions-for-Open-Hardware-&-Source-Development) for more information. 
