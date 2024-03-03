# Will Hall
Computer Science Student @ The University of York 🎓, Computing enthusiast 💻, Lover of Linux & Open Source ♥️, Electronics and Raspberry Pi 🥧, Passionate about de-carbonisation & the energy transition 🗲, Cactus lover 🌵, Keen chef & happily vegetarian since 2022 🧑‍🍳.
***


## 🔭 Current Projects
### Green Impact Energy Monitoring - 📈
> **Stack -** _Python, InfluxDB, Grafana_  
**Started -** _Feb 24_
>
> **Overview -** I'm taking part in a scheme called 'Green Impact' which aims to get students and staff across various institutions involved in sustainability actions. I was placed with the Computer Science departmental team and was keen to bring my love of data and energy to the project. I've been liaising with the University's Building Management Services who have provided access to raw sensor data for the building's utilities. I'm using this data to build graphics and visualizations that can be displayed on the department's video wall. I hope that this will help bring more awareness to viewers and help them better contextualize amounts of energy - as well as allowing us to identify any areas where consumption could be reduced.
>
> **Learning -** This project is in its early stages at the moment but a major point focus for development is getting the data itself. The systems that the university uses for energy management do not offer a public API so data has to be scaped from the user-facing pages. This will also be my first time working with InfluxDB.
>

### Grocy Checkout Partner - 🥕
> **Stack -** _Arduino C++_  
**Started -** _Dec 23_  
>
> **Overview -** Since coming to university, I've been fully in control of my food cupboards for the first time. My love of data, self-hosted software and my hatred of food waste has lead me to the Grocy project ([grocy/grocy](https://github.com/grocy/grocy)) which is a complete stock management system for your groceries. I love how much data and information it provides although the upkeep effort is quite high. Most of our food arrives as a single online order so checking-in products is only a once-per-week affair. Getting your phone out every time you finish a bottle of juice however did feel like bit of a chore (certainly too much so to ask my flatmates to participate). My solution: leave a standalone barcode reader in the kitchen that is connected to the Grocy server via an ESP32 Bridge. I built a kind of dock for the scanner that has buttons for consuming products, marking them as open and adding them to the shopping list.
>
> **Learning -** The challenge here was resource constraint. I knew I wanted to use an ESP32 as oppose to, for example, a Raspberry Pi because I thought it would make the project more reliable, have a lower power consumption and, in some respects, be simpler (e.g. easy hardware interrupts). The trade off though was resource availability - I first had to contend with storage space and have, as yet, been unable to free enough memory to support HTTPS requests to the Grocy server.
>
> **GitLab Repo -** https://gitlab.com/Lime-Parallelogram/grocy-checkout-partner

### York Dialectic Union Website - 🗣️
> **Stack -** _Django, React_  
**Started -** _Oct 23_  
>
> **Overview -** As part of the YorDevs society, I've been part of a small team working on building a website for another student society at the university. We've been working to build a website that will promote the society and conforms to their specification.
>
> **Learning -** This has been my first experience working in a team in which I've not been the project leader. This has been different as I've learned some good habits for little things like branch naming and making PRs that are to be reviewed by others. This project has also relies heavily on external APIs such as Flickr and Eventbrite which I've been working with extensively for the website back-end. I've learned about running periodic jobs in Django and how to make sync jobs for these APIs.
>
> **GitHub Repo -** _private 🔒_

### OctoPrint Multi-Instance - 🐙
> **Stack -** _Django, Angular_   
**Started -** _Feb 23_  
>
> **Overview -** I've had a 3D Printer for many years and have become very proficient with it in this time. For almost all of that time, I've been using OctoPrint (https://octoprint.org/) to control it over the network. Due to my prior knowledge and strong relationship with them, when my school's tech department was looking to invest in a fleet of 3D printers for the students, I was in a good position to advise them on issues they were facing and assist with the setup. I was of course quick to introduce them to OctoPrint having been using it for years however I soon learned that OctoPrint is designed exclusively for controlling a single printer. To this end, I have designed an aggregation interface that creates multiple instances of OctoPrint using Docker and provides management functionality of the containers.
>
> **Learning -** The best learning experience from this project was the extra responsibility that comes with developing for a 'client'. I discovered just how much more testing is required when deployment is to a system that is beyond my control and fell foul of the temptation to deliver the software too quickly without adequate testing. I also learned more about permissions in Linux (in particular, cgroups) as I worked to allow the Docker container to communicate on a serial port. It has also a good exercise in interface design; early versions of the software had some very esoteric interaction sequences which lead to a very poor UX. After a module in my university highlighted the importance of interface design, I returned to the drawing board (literally) and re-designed the entire settings interface.
>
> **GitLab Repo -** https://gitlab.com/Lime-Parallelogram/octoprint-multi-instance

### Parallel Computing Services - 🖥️
> **Started -** _May 22_
>
> **Overview -** In a slight deviation from programming projects, I started a venture that offered general computer help to people in the local area. Projects that I have undertaken as part of this are, for example, upgrading someone's computer with an SSD, diagnosing 3D printer issues and recovering data from a WD MyCloud after the service was discontinued and the customer lost access to their data. I've also done some academic tutoring under this brand.
>
> **Learning -** This project taught me a lot about advertising and outreach, it helped me gain confidence interacting with strangers and made me understand the stress of making recommendations to people: the worry that you have made the wrong suggestion. I have also had to develop my record keeping in order to produce accurate summary sheets, cost breakdowns and invoices to give to my clients.
>

## 🕰️ Past Projects
### Pirate Game - 🏴‍☠️
> **Stack -** _Python Flask, Vanilla Web Stack (HTML,CSS,JS)_   
**Project Length -** _6 months_  
>
> **Overview -** In an effort to gain experience in collaborative development, this project is an attempt to remaster one of our favorite pen-and-paper games from school maths lessons. Pirate Game Live is a Flask-based online application. The game is largely luck-based and works by at inviting users to place items in a grid. A random grid square is selected and the user must use the items in those squares against other users. For example, the user chooses a target for their 'steal' and they take all of the target's money.  
>
> **Learning -** This project has been an amazing opportunity to not only learn more about Flask and improve my knowledge of web-development and web-languages but also to develop my knowledge of deploying to the internet using a VPS. The largest learning curve came with the live communication. This was achieved using websockets which allow each of the clients to participate in live games but also introduce many edge cases, such as dealing with a user leaving prematurely. In the years since I mothballed this project, I have learned just how challenging it was to write the entire game in vanilla HTML, CSS and JS. I have started refactoring the project with Angular as the front-end but this too is mostly on the backburner.
>
> **GitHub Repo -** https://github.com/A-Level-Personal-Code-Collab/PirateGame  
**Live Website -** https://pirategame.live/

### octoClock - 🕘
> **Language -** _Python_  
> **Overview -** The OctoClock is another hardware project of mine for which I have been developing custom software. It is a glass wall clock equipped with a ring of addressable RGB LEDs. A Raspberry Pi is used for control and the primary software functionality is to integrate with the OctoPrint API in order to display the remaining time on a user's 3D Printer.
>
> **Learning -** I wanted the software to be as extensible as possible so that other functionality could be added later. Designing an architecture that would facilitate this has been a great challenge, especially with the added complexity that all configuration must be possible while the clock is not booted, allowing it to be used on even very restricted networks.  

## 🧑🏾‍🤝‍🧑🏼 Future Collaboration
I use a vast array of open source software day to day and I am very aware of the importance of giving back to these. For a long time, I have been intimidated by the fact that many of my favorite apps use stacks or languages that I am not familiar with. I know this is a poor excuse and I have been inspired to do more in this area by a recent trip to FOSDEM.

## 🌱 Developing / Learning
💬 Matrix & The Fediverse - I am incredibly passionate about the open web and I truly believe that decentralization is the gold standard, especially for chat. I want to start using Matrix with as many people as I can, understand its benefits, shortfalls, and the intricacies of how it works.  
📃 Logging & Monitoring - I have quite a lot of servers deployed but I have never invested the time to set up proper logging and monitoring. I recently discovered a string of attempted brute for logins on my email server and this has encouraged me to keep a closer eye on things.  

## 📪 Socials / Contact :
🦊 GitLab - https://gitlab.com/Lime-Parallelogram  
🐈‍⬛ GitHub - https://github.com/Lime-Parallelogram  
🐘 Mastodon - https://mastodonapp.uk/@limeparallelogram  
🔗 LinkedIn - https://www.linkedin.com/in/will-hall-a64874236  
🎞️ YouTube - http://www.youtube.com/@limeparallelogram7221  

## 🎈 Fun Facts:
- Favorite meals: Pesto pasta, Home-made pizza in the Ooni oven, Tofu ramen 🍲
- Favorite radio programme: BBC Radio 2 Sounds of the 80s w. Gary Davis 📻
- My company name, Lime Parallelogram, was created from my childhood nickname - Lime 🟢
- I took 4 A-Levels: Maths, Further Maths, Physics & Computer Science 4️⃣

<!--
**Lime-Parallelogram/Lime-Parallelogram** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
