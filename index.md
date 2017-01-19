 <img src="https://raw.githubusercontent.com/google/physical-web/master/documentation/images/logo/logo-black.png" alt="Physical Web logo" style=" width="100" height="100""/>

**## UPDATES:**

On 22.4.2016:

Dear students from around the world.

Today, April 22, 2016, Google has communicated to all of you that presented proposals to our project about the scholarships.
Thank you to everybody that has contacted and interacted with us. More than 120 diferent proposals where received initially, than became 90 final proposals on the Google system.

Congratulations to the choosen ones, and thank your to all the rest, your proposals were generally so interesting but finally we do have a very limited number of spots.

_**The GSoC Physical Web project mentor team.**_

On 25.3.2016 Google system closed the window application for would be students.
We hope most of you have presented a final PDF and get the Complete flag on the GSoC system. Goog luck for everybody !

On 19.3.2016 a guide to Physical Web has been provided. [Please read this guide to Physical Web](https://docs.google.com/document/d/1VC9umaw9TItV31WrcX0eJ9xVsfXXQoWvUjuSqWXmH8A/edit#).

On 14.3.2016 opened the registration period at GSoC site. We hope all of the students that have been contacting us apply to the system and fill up his data and project proposal. We'll be contacting you all ASAP, but remember that lots of students have contacted us and that all the communications from there will always happen through the GSoC portal in private or public way between mentors and students.
So, point your browser to [Main GSoC 2016 Site](https://summerofcode.withgoogle.com) and register when it's open. Good luck to all !!!

### What is the Physical Web and the Physical Web Project?
The Physical Web is an approach to unleash the core superpower of the web: interaction on demand. People should be able to walk up to any smart device - a vending machine, a poster, a toy, a bus stop, a rental car - and not have to download an app first. Everything should be just a tap away. 

The number of smart devices is going to explode, and the assumption that each new device will require its own application just isn't realistic. We need a system that lets anyone interact with any device at any time. The Physical Web isn't about replacing native apps: it's about enabling interaction when native apps just aren't practical.

The Physical Web Project is the Google Summer of Code proposal for university students interested in developing applications around that technology. The Physical Web Project, while making use of [Physical Web](https://google.github.io/physical-web/) software, does not develop the Physical Web code-base itself. Physical Web is an open standard that everyone can use. By creating a common web standard that any device can use to offer interaction, a new range of services becomes possible. Instead, the Physical Web Project works on extending the Physical Web system with open source software enabling open source applications.


### What kinds of skills or experience should you bring?
* Programming in Java, JavaScript, HTML, CSS3 or other languages.
* Experience with Mobile environment, including Android.
* Experience with Wireless development, including Bluetooth Low Energy.
* Experience in small PC like systems such as Raspberry Pi, Arduino, Beagle Board.
* Technical experience with other Internet of Things systems.

### Suggested GSoC 2016 Project Ideas

We have plenty of great things you could work on, here are some briefly described and to be developed, but first take a look at the [ideas page](http://google.github.io/physical-web/cookbook/) from the main web site. 
And also remember that you can propose us with your ideas.

* Person identifier for Emergency situations  
Idea: In order to identify people in emergency or disaster situations (the beacon will link to a website with the user's health profile). The web has different profiles to show. -For normal people, police, or emergency people as a doctor or a nurse.
To be coded: A platform with users registration, tahta generates urls for the associated beacons running on a server, the frontend, the android aplication with login profile and link to liquid galaxy.  
Skills needed: nodeJS, angularJS, bootstrap, html, and android.

* Smartphone Auto Setting  
Idea: Useful to autoset a preselected settings on the phone. E.g. When a user arrives to a place, its smartphone reads a particular beacon and it starts the silent mode.  
To be coded: android app that automatically starts preselected settings on the phone
Skills needed: Android  

* Guide me for blind people  
Idea: For people with visual problems, some beacons in the path could help to provide further information about the place or to check if it is the correct destination, it can help to ensure that the beacon provides extra information about the place until the next beacon (if there are obstacles, stairs, wide corridor, etc.)  
To be coded: Android app that detects different physical web beacons, check the distance and gives information via voice.
Skills needed: nodeJS, angularJS, bootstrap, html

* Local Air & Weather Info  
Idea: To check weather information or other open data information, when a user arrives to a place, the beacon can tell, temperature, level of air pollution, etc.  
To be coded: Android app that check a physical web beacon and gives relevant open data information with push notifications. Backend to set locations beacons and information.  
Skills needed:  nodeJS, angularJS, bootstrap, html

* Interactive License Plate for Drones  
Idea: Drones are gonna be everywhere soon moving goods, medicines, and many more things. As we have the right to know what’s going on over our heads, the idea is that every drone has a PW beacon pointing to an url with information about his trip. This web page has to be dynamically generated each time the drone departs from a place to another, and if it’s in the range of the BLE radio, the user will have different informations about the drone and his trip or a fixed virtual license plate.  
To be coded: The application has to deal with generating a backend for different users to register his drones, and have a link to a multi drone system. Also the front end consisting on a mobile site done in Polymer, Html5, or similar modern web languages with Material Design aspect.  
Skills needed: Python.  

* BYOP (Bring Your Own POIS)  
Idea: The many Google Liquid Galaxy immersive and panoramic Google Earth viewer instances installed around the world are visited daily by school or other kind of groups. The teacher or guide usually will want to show up certain contents. The idea is to develop a backend where you can enter locations in coordinates, for different users, generating the standard XML Point of Interest file of a Liquid Galaxy on a web url. A PW beacon own by the professor or guide will trigger a small hardware arduino or rpi based in a Liquid Galaxy system to download those POIS for a session.  
To be coded: the multi user backend to enter the POI coordinates and metadata, the hardware script for recognizing a PW url, and the connection to a Liquid Galaxy.   
Skills needed: Python, whatever language you use for the hardware.  

<!--
### Mentors - Who is going to help you?

* Andreu Ibañez  
Andreu is a freelancer technologist with 30 years of experience in the IT sector. Enjoying constantly innovating and creating new technologies for such diverse areas as clusters display, drones and lasers where he is currently engaged. He specializes in the ecosystem of Google, where he is mentor of Google Summer of Code with projects such as Liquid Galaxy and DC Extractor, Google Glass Explorer with Scalardrone startup, and has set up a unique laboratory in the world to do projects with various technologies where we can find Google maps integrated with the Liquid Galaxy technology. He is the founder and organizer of the Google Developers Group GDG Lleida and co-organizer of GDG in Spain, national and international speaker about new technologies and an expert on Google.
He is Chairman and Founder of Lleida Drone, association on drones  technology created in 2011. He also works as Advisor in strategy, marketing and technology in several Spanish startups, as Remotte Labs, Inc Subtix, VT-LAB and Rectangular Studios.  

* Cándido Caballero-Gil  
Teacher and Researcher at University of La Laguna, with wide experience in R&D+i at Computer Science and Programing sector (Android), I have been always working developing, transferring and promoting innovative technologies. 
I teach in Computer Science and Engineering and I am co-organizer in the Google Developer Group (GDG) in Tenerife.
Also I have been founder of non fully successful startups, but I go on.
From an educational point of view, I am Ph.D. in Computer Science with a Thesis about Security in VANET(Vehicular ad-hoc Networks).
Nonetheless I have been keeping an eye on continuous education, with additional training courses in project management, entrepreneurship or educational topics.  
From a career point of view, I have been working in most of the stages of R&D+i, including software development, project management (medium size projects), product definition, some marketing and business development at several R&D proyects both for university and private sector. 

* Francisco Martín-Fernández  
 received his B.Sc. degree in Computer Science at the University of La Laguna (Spain) in 2011. He is being supported by the Spain Minister under a 4 year scholarship. He is researching on security in Vehicular Ad-hoc Networks and Internet of Things. He belongs to the CryptULL research group devoted to the development of projects on cryptology. He plans to present his Thesis in 2016.  
Topics: Cryptography, Wireless Communications in Vehicular Networks, Authentication in Internet of Things, Trust Algorithms.  
He is also founder and Lead Organizer in the Google Developer Group Tenerife, from Spain.
-->

### Interested? What you have to do next...

If you want to make a proposal as student, point your browser to the [main GSoC 2016 site](https://summerofcode.withgoogle.com/) and follow the instructions there. If you need to reach us directly for any cause, contact us by [email](mailto://physicalwebproject@gmail.com).

Good Luck!

Physical Web Project GSoC Organizer and mentors