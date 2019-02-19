# Awesome Fabacademy

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![Travis build status](https://travis-ci.org/Academany/awesome-fabacademy.svg?branch=master)](https://travis-ci.org/Academany/awesome-fabacademy)

> A curated list of Fab Academy Resources

## Contents

- [Awesome Fabacademy](#awesome-fabacademy)
  - [Contents](#contents)
  - [Project Management](#project-management)
    - [Project management tools](#project-management-tools)
    - [Project management techniques](#project-management-techniques)
  - [Version Control](#version-control)
    - [Protocols](#protocols)
      - [Git](#git)
      - [Subversion](#subversion)
      - [Mercurial](#mercurial)
    - [Hosting platforms](#hosting-platforms)
  - [CAD](#cad)
    - [2D](#2d)
    - [3D](#3d)
      - [Mesh modeling](#mesh-modeling)
      - [Parametric modeling](#parametric-modeling)
    - [Vector](#vector)
    - [Wireframes & UX Design](#wireframes--ux-design)
    - [Raster](#raster)
  - [Electronics design](#electronics-design)
    - [EDA Packages](#eda-packages)
    - [KiCAD resources](#kicad-resources)
    - [EAGLE Resources](#eagle-resources)
    - [Simulators](#simulators)
    - [Part Search](#part-search)
    - [Development Board Retailers](#development-board-retailers)
    - [Books](#books)
    - [Blogs](#blogs)
  - [Electronics production](#electronics-production)
    - [Soldering](#soldering)
    - [Inventory Management and Purchasing](#inventory-management-and-purchasing)
  - [PCB Batching Services](#pcb-batching-services)
  - [Related Awesome Lists](#related-awesome-lists)
  - [Symbols](#symbols)
  - [Contribute](#contribute)
  - [License](#license)

## Project Management

### Project management tools

- :white_check_mark: [GitLab](https://www.gitlab.com/)- Clone of GitHub, has issue trackers, kan ban boards and milestones
- [Redmine](http://www.redmine.org/) - Popular choice for software projects, Ruby on Rails
- [Trac](http://trac.edgewall.org/)- Similar to Redmine but written in Python, has Gantt charts
- [OpenProject](https://www.openproject.org) - Project collaboration software, has Gantt charts
- [Gantt Project](https://www.ganttproject.biz/) - Linux project management app
- :moneybag: [Microsoft Project](https://products.office.com/en/project/project-and-portfolio-management-software) - mostly used by professionals
- :moneybag: :white_check_mark: [Trello](https://trello.com) Kan Ban boards and team collaboration
- :moneybag: [Basecamp 3](https://basecamp.com) - good for small teams
- :moneybag: [Asana](https://asana.com/) - popular in business

### Project management techniques

- [Agile](https://en.wikipedia.org/wiki/Agile_software_development)
- [SCRUM](https://en.wikipedia.org/wiki/Scrum)
- [Waterfall](https://en.wikipedia.org/wiki/Waterfall_model)

## Version Control

### Protocols

#### Git

Docs

- [Git magic book](http://www-cs-students.stanford.edu/~blynn/gitmagic/) by Ben Lynn.
- [Pro Git book](https://git-scm.com/book) by Scott Chacon and Ben Straub.
- [Git How to](https://githowto.com/) - a guided tour that walks through the fundamentals of Git.
- [Git Cheatsheet](http://ndpsoftware.com/git-cheatsheet.html) - Git Cheatsheet from NDP software.
- [Git Immersion](http://gitimmersion.com/) - is a guided tour that walks through the fundamentals of Git.

Clients

- [GitHub Desktop](https://desktop.github.com/) - official GitHub client.
- [SmartGit](http://www.syntevo.com/smartgit/) - stand-alone or portable Git client.
- [TortoiseGit](https://tortoisegit.org/) - Windows Explorer shell extension.
- [GitKraken](https://www.gitkraken.com)
- [Git Extensions](http://gitextensions.github.io/) - Windows Explorer extension.
- [Legit](http://www.git-legit.org/) - command-line interface for Git, optimized for workflow simplicity.
- [Tower](https://www.git-tower.com/mac) - powerful client for Mac and Windows

#### Subversion

- [SVN](http://subversion.apache.org/) - popular centralized version control system.
- [SVN Red book](http://svnbook.red-bean.com/) - you should to start here.

Clients

- [TortoiseSVN](https://tortoisesvn.net/) - Windows Explorer shell extension
- [Version Control for engineers](http://soft.postpdm.com/)

#### Mercurial

- [Mercurial SCM](https://www.mercurial-scm.org/) - Older protocol also used in Fab Academy up to 2015
- [TortoiseHg](http://tortoisehg.bitbucket.org/) - Windows Explorer shell extension

### Hosting platforms

Mostly :free: with :moneybag: options

- [Fab Cloud](https://gitlab.fabcloud.org) - Free hosting for Fab labs - Sponsored by Fab Foundation
- [Github.com](https://github.com) - The most used for Open source projects
- [Gitlab.com](https://gitlab.com) - Open source hosting similar to Github, based on Gitlab
- [BitBucket](https://bitbucket.org/) - Commercial GIT provider by Atalassian
- [Sourceforge](https://sourceforge.net/) - Top host for opensource projects before Github came out

## CAD

### 2D

- [AutoCAD](https://www.autodesk.com/products/autocad/overview) :moneybag: :school:
- [Draftsight](https://www.3ds.com/products-services/draftsight-cad-software/free-download/) Free software from Dassault, similar to Autocad features

### 3D

#### Mesh modeling

- [3DS Max]
- [Maya]
- [Lightwave]
- [Cinema 4D]
- [Blender]

#### Parametric modeling

- [FreeCAD](https://www.freecadweb.org/) :white_check_mark: similar to Solidworks, growing community
- [OpenSCAD](http://www.openscad.org/) text-based CSG modeling, used by many open source projects
- :moneybag: [Rhinoceros](https://www.rhino3d.com/) used by architects and designers, along with the [Grasshopper](https://www.grasshopper3d.com/) free plugin
- :moneybag: [Fusion 360](https://www.autodesk.com/products/fusion-360/overview) :school: very powerful, cloud integration, integrated mesh, nurbs, surfaces, parametric, CAM tools
- :moneybag: [Solidworks](https://www.solidworks.com/) :school: Very advanced and complex, used for industrial applications

### Vector

- [Inkscape](https://inkscape.org/) best option for open-source lovers, many extensions, programming in python
- :moneybag: [Illustrator](https://www.adobe.com/products/illustrator.html) standard software for professional graphic designers
- :moneybag: [Corel Draw](https://www.coreldraw.com/it/) one of the oldest, still used often in the print & advertising industry

### Wireframes & UX Design

- :moneybag: [Wireframe.cc](https://wireframe.cc) web based tool
- :moneybag: [Balsamiq Mockups](https://balsamiq.com/) one of the best for low-fi mockups
- :moneybag: [OmniGraffle](https://www.omnigroup.com/omnigraffle) popular diagramming app for mac
- :moneybag: [Sketch](https://www.sketchapp.com/) trendy app for modern UI designers, MAC only
- :moneybag: :free: [Adobe XD](https://www.adobe.com/it/products/xd.html) good alternative to Sketch for other platforms

### Raster

- [Gimp](https://www.gimp.org/) - popular, and the only option for Linux users
- :moneybag: [Photoshop](https://www.adobe.com/products/photoshop.html) - de facto standard for image editing
- :moneybag: [LightRoom](https://www.adobe.com/it/products/photoshop-lightroom.html) - photo editing and organization
- :moneybag: [Pixelmator](https://www.pixelmator.com/pro/) - cost effective image editing for Mac

## Electronics design

### EDA Packages

- [KiCAD](http://kicad-pcb.org/) - Open source EDA package with push and shove router, differential pairs and much more.
- [Eagle](https://www.autodesk.com/products/eagle/overview) - One of the most popular EDA packages due to it's (board size restricted) free version.
- [Design Spark PCB](https://www.rs-online.com/designspark/pcb-software) - Gratis EDA package without restrictions, sponserd by RS Components.
- [Altium Circuit Maker](https://circuitmaker.com/) - Free package from the maker of the go to pro software.
- [gEDA](http://geda-project.org) - Another open source package, good for people that like scripting and makefiles, Linux and BSD only.
- [DipTrace](https://diptrace.com) - Quality Schematic Capture and PCB Design software with (pin and signal layer restricted) free version.
- [LibrePCB](https://librepcb.org/) - A new, powerful and intuitive EDA tool for everyone, cross-platform and GNU GPLv3.

:moneybag: Commercial

- [Altium Designer](https://en.wikipedia.org/wiki/Altium_Designer)
- [National Instruments Ultiboard](https://en.wikipedia.org/wiki/NI_Ultiboard)

### KiCAD resources

- [Xesscorp's list of KiCAD 3rd party tools](https://github.com/xesscorp/kicad-3rd-party-tools)
- [Contextual Electronics' Shine on You Crazy KiCad](https://contextualelectronics.com/courses/shine-on-you-crazy-kicad/) - Beginner video tutorial that gets you to a manufactured board as quickly as possible.
- [Contextual Electronics' Getting to Blinky Tutorial](https://www.youtube.com/playlist?list=PLy2022BX6Eso532xqrUxDT1u2p4VVsg-q) - A more comprehensive beginner to intermediate video tutorial.
- [KiCAD.info Forums](https://forum.kicad.info) - User discussion and help forum.
- [Keyboard PCB Guide](https://github.com/ruiqimao/keyboard-pcb-guide) - Comprehensive written tutorial that takes you through creating a keyboard PCB.
- [Cheatsheet](https://silica.io/static/downloads/kicad-cheatsheet.pdf) (also [in landscape](https://silica.io/static/downloads/kicad-cheatsheet-landscape.pdf)) - Short PDF that goes over the menus and keyboard shortcuts for the most common operations.
- [Footprint Collection](https://github.com/monostable/kicad_footprints) - Collection of all the KiCAD footprints available online and some scripts to manage them.

### EAGLE Resources

- [List of ULPs everyone should know](https://www.element14.com/community/community/cadsoft_eagle/blog/2015/01/19/eagle-ulps-every-user-should-know)
- [Adafruit Eagle Library](https://github.com/adafruit/Adafruit-Eagle-Library)
- [SparkFun Electronics Eagle Libraries](https://github.com/sparkfun/SparkFun-Eagle-Libraries)

### Simulators

- [LTSpice](http://www.analog.com/en/design-center/design-tools-and-calculators/ltspice-simulator.html) - The industry standard free SPICE circuit simulator from Linear Technologies.
- [Ngspice](http://ngspice.sourceforge.net/) - Open source SPICE circuit simulator.
- [Circuit JS](http://www.falstad.com/circuit/circuitjs.html) - Open source online simulator for simpler circuits with live interactivity and visualization.
- [Every Circuit](http://everycircuit.com) - Free to try online, visual, interactive circuit simulator for simpler circuits.
- [Qucs](http://qucs.sourceforge.net/) - Open source integrated circuit simulator for DC, AC, S-parameter, noise analysis, etc.
- [iCircuit](http://icircuitapp.com/) - Easy to use electronic circuit simulator, its advanced simulation engine can handle both analog and digital circuits and features realtime always-on analysis.

### Part Search

- [Octopart](https://octopart.com) - Probably the most well known part search engine.
- [Findchips](https://www.findchips.com/) - Part search from Supply Frame.
- [Parts.io](https://parts.io/) - Another search engine from Supply Frame geared towards discovering new parts.
- [Buyparts.io](http://buyparts.io) - A new contender from the creator of the datasheetarchive.com. Is aimed at hobbyists and seems to be better at incorporating sources such as Ebay and Aliexpress.

### Development Board Retailers

- [Sparkfun](https://www.sparkfun.com/) - Retailer and designer of open source electronics development boards and other equipment and materials with excellent accompanying tutorials.
- [Adafruit](https://www.adafruit.com/) - Another retailer and designer with excellent selection and tutorials.
- [Tindie](https://www.tindie.com) - Marketplace for electronics makers to sell low volume batches of their own designs.

### Books

- [Getting Started in Electronics](https://www.amazon.com/Getting-Started-Electronics-Forrest-Mims/dp/B001QTFKK4) by Forrest Mims
- [The Art of Electronics](https://www.amazon.com/Art-Electronics-Paul-Horowitz/dp/0521809266) by Paul Horowitz and Winfield Hill
- [Make: Electronics](https://www.amazon.com/Make-Electronics-Discovery-Charles-Platt/dp/0596153740) by Charles Platt
- [Make: More Electronics](https://www.amazon.com/Make-Electronics-Journey-Amplifiers-Randomicity/dp/1449344046) by Charles Platt
- [Practical Electronics for Inventors](https://www.amazon.com/Practical-Electronics-Inventors-Fourth-Scherz/dp/1259587541) by Paul Scherz and Simon Monk
- [The AVR Microcontroller and Embedded Systems: Using Assembly and C](https://www.amazon.com/AVR-Microcontroller-Embedded-Systems-Electronics/dp/0138003319) by Muhammad Ali Mazidi, Sarmad Naimi and Sepehr Naimi
- Encyclopedia of Electronic Components Series by Charles Platt
  - [Volume 1 - Resistors, Capacitors, Inductors, Switches, Encoders, Relays, Transistors](https://www.amazon.com/Encyclopedia-Electronic-Components-Capacitors-Transistors/dp/1449333893)
  - [Volume 2 - LEDs, LCDs, Audio, Thyristors, Digital Logic, and Amplification](https://www.amazon.com/Encyclopedia-Electronic-Components-Thyristors-Amplification/dp/1449334180)
  - [Volume 3 - Sensors for Location, Presence, Proximity, Orientation, Oscillation, Force, Load, Human Input, Liquid ... Light, Heat, Sound, and Electricity](https://www.amazon.com/Encyclopedia-Electronic-Components-Orientation-Oscillation/dp/1449334318)
- Forrest Mims Engineer's Mini Notebook Series
  - [Volume 1 - Timer, Op Amp, and Optoelectronic Circuits & Projects](https://www.amazon.com/Timer-Amp-Optoelectronic-Circuits-Projects/dp/0945053290)
  - [Volume 2 - Science and Communication Circuits & Projects](https://www.amazon.com/Science-Communication-Circuits-Projects-Forrest/dp/0945053320)
  - [Volume 3 - Electronic Sensor Circuits & Projects](https://www.amazon.com/Electronic-Circuits-Projects-Engineers-Notebook/dp/0945053312)
  - [Volume 4 - Electronic Formulas, Symbols & Circuits](https://www.amazon.com/Electronic-Formulas-Symbols-Circuits-Forrest/dp/0945053304)
- [Zero to Maker: Learn (Just Enough) to Make (Just About) Anything](https://www.amazon.com/Zero-Maker-Learn-Enough-Anything/dp/1449356435) by David Lang

### Blogs

- [Hackaday](https://hackaday.com) - Probably the most popular blog covering electronics and hardware hacking with a whole staff of writers.
- [bunniestudios.com](https://www.bunniestudios.com) - Andrew 'Bunnie' Huang covers hardware hacking, open hardware, manufacturing and more.
- [Bald Engineer](https://www.baldengineer.com) - Project logs, tutorials and articles about electronics and embedded software by James Lewis.
- [Rheingold Heavy](https://rheingoldheavy.com) - More project logs, tutorials and articles about electronics and embedded software, these ones by Dan Hienzsch.

## Electronics production

### Soldering

- ["skill" tag on learn.sparkfun.com](https://learn.sparkfun.com/tutorials/tags/skill) - A wide variety of technical tutorials on various EE related skills.
- [Soldering is Easy](https://mightyohm.com/blog/2011/04/soldering-is-easy-comic-book/) - Comic book that goes over the basics of soldering that has been translated into quite a few languages.

### Inventory Management and Purchasing

- [1-click BOM](https://1clickbom.com) - Browser extensions that automates purchasing and part searching.
- [Partsbox.io](https://partsbox.io) - Web service to manage your part inventory with a nice user interface and Octopart integration.
- [Partkeepr](https://partkeepr.org) - Open source web service for managing your part inventory with parametric search and automatic datasheet import.
- [Part-DB](https://github.com/Part-DB/Part-DB) - Another open source web service for managing part inventory with a permission system and a good barcode generator.

## PCB Batching Services

- [PCB Shopper](https://pcbshopper.com/) - Comparison service for quite a lot of different PCB batching and assembly services.
- [OSH Park](https://oshpark.com) - Low cost PCB batching service with high quality boards with a signature purple silkscreen.
- [Aisler](https://aisler.net) - Affordable quality circuit boards made in and shipped from Europe (Germany).
- [Dirty PCBs](http://dirtypcbs.com/store/pcbs) - Low cost PCB batching service that prides itself on its "dirty" quality.
- [Seeed Studio Fusion](https://seeed.com) - Cheap PCB manufacturing also in large quantities, consulting services

## Related Awesome Lists

- [Awesome Project Management](https://github.com/brianjking/awesome-project-management)
- [Awesome Arduino](https://github.com/Lembed/Awesome-arduino)
- [Awesome 3D Printing](https://github.com/ad-si/awesome-3d-printing)
- [Awesome VCS Tools](https://github.com/postpdm/awesome-vcs-tools)
- [Awesome Electronics](https://github.com/kitspace/awesome-electronics)
- [Open Electronics](https://github.com/intajay/open-electronics)
- [Awesome Fabrication](https://github.com/ad-si/awesome-fabrication)

## Symbols

- :moneybag: commercial
- :school: free for education
- :white_check_mark: recommended
- :free: commercial but with free license (possibly limited)

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, original author has waived all copyright and
related or neighboring rights to this work.
