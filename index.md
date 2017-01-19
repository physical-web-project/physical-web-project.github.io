![](https://storage.googleapis.com/rm-wp-production//2016/05/AAEAAQAAAAAAAAW4AAAAJGEzMjZlMmMxLWVkYTktNDYxMi04NTY5LWMwNzQzZmRjNTlkMw.png)

**## UPDATES:**

On 19.1.2016:

Dear students from around the world.

The Physical Web GSoC mentor team has presented again the project with the support of Google Chrome team to the GSoC. Let’s wait for news to start the development of this year projects.

### What is the Physical Web and the Physical Web Project?

The Physical Web is an approach to unleash the core superpower of the web: interaction on demand. People should be able to walk up to any smart device - a vending machine, a poster, a toy, a bus stop, a rental car - and not have to download an app first. Everything should be just a tap away. 

The number of smart devices is going to explode, and the assumption that each new device will require its own application just isn't realistic. We need a system that lets anyone interact with any device at any time. The Physical Web isn't about replacing native apps: it's about enabling interaction when native apps just aren't practical.

The Physical Web Project is the Google Summer of Code proposal for university students interested in developing applications around that technology. The Physical Web Project, while making use of [Physical Web](https://google.github.io/physical-web/) software, does not develop the Physical Web code-base itself. Physical Web is an open standard that everyone can use. By creating a common web standard that any device can use to offer interaction, a new range of services becomes possible. Instead, the Physical Web Project works on extending the Physical Web system with open source software enabling open source applications.


### What kinds of skills or experience should you bring?

* Programming in Java, JavaScript, HTML, CSS3 or other languages.
* Experience with Web Bluetooth.
* Experience with Mobile environment, including Android.
* Experience with Wireless development, including Bluetooth Low Energy.
* Experience in small PC like systems such as Raspberry Pi, Arduino, Beagle Board.
* Technical experience with other Internet of Things systems.

### Suggested GSoC 2017 Project Ideas

We have plenty of great things you could work on, here are some briefly described and to be developed, but first take a look at the [ideas page](http://google.github.io/physical-web/cookbook/) from the main web site. 
And also remember that you can propose us with your ideas.

* JSON AutoDescriptive AutoDiscover Objects  

*Idea*: Hundreds of objects surround us daily in everyday environments. The idea is to be able to label the hundreds of objects that are around us and to have a control of all their relationships. For example, in a toy room, we can label the toys with a Physical Web. Then, using an application, we can know their characteristics, their information and their relationships with other toys in the own environment, such as a remote car with its control. We could generate an specific format, using the JSON standard to label the objects and create their relationships.  
To be coded: The application has to deal with generating a backend to manage the objects and a web application to query the information about this near objects.

*Skills needed*: Programming in JavaScript (Node.js and Angular.js), HTML5 and CSS3. Experience with Wireless development, including Bluetooth Low Energy.

* PW Museum Backend

*Idea*: To push the use of Physical Web uses in museums, exhibitions and similar use cases, the idea is to develop a simple CMS that manages basic types of contents and info cards,  linking them to a PW beacon. Minimal contents type are text, images, audio and video. A map handling solution has to be included, to allocate and control the beacons deployed. Analytics will be welcome. The system has to handle the proximity to the beacon and refresh to the nearer contents with accuracy and thinking about the user behaviour.
To reach the push goal this CMS has to be implemented using free services, we think of a Android Application as the core manager and CMS and Google Drive, Firebase (Spark) or similar free systems as database.

*Skills needed*: Android, Firebase, Google Drive API.

* Hospital Routing

*Idea*: When going to a hospital to visit a relative or a friend we usually get lost as all the corridors look the same, sometimes we do not even know it which floor we are! The main idea here is, using PW beacons, develop a web or mobile app that tells us where we are. In that map we will see several switched off points and a bright one, telling us our current position. When we keep walking, we need to know to which beacon we are approaching and, when we are near it, refresh the layout to update the user’s position. It is important to keep control of the BT signal to do so and update the UI in the most user friendly way possible.

*Skills needed*: Programming in JavaScript (Node.js and Angular.js), HTML5 and CSS3. Experience with Wireless development, including Bluetooth Low Energy.

* Assistive Scanner

*Idea*: Create a new PW scanner for the blind that looks for a unique marker (e.g. URL param &audio) that marks the web page as containing audio. The scanner loads the page, looking for JSON+LD which points to the audio. As user has this new scanner open, it reads aloud what it finds. Existing users can use exactly the same beacons (and standard PW scanner) to look at typical HTML pages.

*Skills needed*: Web Languages.

* Smartphone Auto Setting  

*Idea*: Useful to autoset a preselected settings on the phone. E.g. When a user arrives to a place, its smartphone reads a particular beacon and it starts the silent mode.  
To be coded: android app that automatically starts preselected settings on the phone

*Skills needed*: Android, Firebase.

* Guide me for blind people  

*Idea*: For people with visual problems, some beacons in the path could help to provide further information about the place or to check if it is the correct destination, it can help to ensure that the beacon provides extra information about the place until the next beacon (if there are obstacles, stairs, wide corridor, etc.)  
To be coded: Android app that detects different physical web beacons, check the distance and gives information via voice.

*Skills needed*: nodeJS, angularJS, bootstrap, html

* Local Air & Weather Info  

*Idea*: To check weather information or other open data information, when a user arrives to a place, the beacon can tell, temperature, level of air pollution, etc.  
To be coded: Android app that check a physical web beacon and gives relevant open data information with push notifications. Backend to set locations beacons and information.  

*Skills needed*:  nodeJS, angularJS, bootstrap, html

* Interactive License Plate for Drones  

*Idea*: Drones are gonna be everywhere soon moving goods, medicines, and many more things. As we have the right to know what’s going on over our heads, the idea is that every drone has a PW beacon pointing to an url with information about his trip. This web page has to be dynamically generated each time the drone departs from a place to another, and if it’s in the range of the BLE radio, the user will have different informations about the drone and his trip or a fixed virtual license plate.  
To be coded: The application has to deal with generating a backend for different users to register his drones, and have a link to a multi drone system. Also the front end consisting on a mobile site done in Polymer, Html5, or similar modern web languages with Material Design aspect.  

*Skills needed*: Python.  

### Open ideas

We want students proposal based on some technologies that will be a hit this 2017.

* [Web Bluetooth](https://www.chromestatus.com/feature/5264933985976320),
which is about to ship in Chrome 56 in February 2017. 
[Here](https://www.chromestatus.com/feature/5264933985976320) you can find the description of the web bluetooth API.
* [Angular.io](https://medium.com/google-developer-experts/the-web-bluetooth-module-for-angular-9336c9535d04#.gtzjr05kb),
Also we would like to see student proposal that uses Angular as the framework for the GUI.
[Here](https://medium.com/google-developer-experts/the-web-bluetooth-module-for-angular-9336c9535d04#.gtzjr05kb) you can find an idea
* [RFDuino](https://gist.github.com/scottjenson/31e8f82cc163d34ffac176023bf1f18d),
And last but never least IoT based projects like this [RFDuino](https://gist.github.com/scottjenson/31e8f82cc163d34ffac176023bf1f18d), and arduino sketch that replies to a web bluetooth request

Remember that the ideas you proposed us have to be enough consistent for a 3+ months of development, as the GSoC agenda marks.

### GSoC 2016 Projects Developed

* [Project IBRI Drone](https://github.com/LiquidGalaxyLAB/IBRI_Drone)

![](https://1.bp.blogspot.com/-kjyNsXXnHnU/VwjpqkXmLkI/AAAAAAADyv0/xeu6uSXkFKQ0UveRYQ163LjGGLkvVoO6A/s1600/IBRIlogo.png)

*Student*: Moisés Lodeiro Santiago

The many Google Liquid Galaxy immersive and panoramic Google Earth viewer instances installed around the world are visited daily by school or other kind of groups. The teacher or guide usually will want to show up certain contents. The idea was to develop a backend where you can enter locations in coordinates, for different users, generating the standard XML Point of Interest file of a Liquid Galaxy on a web url. A PW beacon own by the professor or guide will trigger a small hardware arduino or rpi based in a Liquid Galaxy system to download those POIS for a session.  

**More info**: [IBRI Drone Web](https://github.com/LiquidGalaxyLAB/IBRI_Drone)

* [Project BYOP](https://github.com/LiquidGalaxyLAB/Liquid-Galaxy-POIs-Controller/blob/master/GSOC16.md)

![](https://lh3.googleusercontent.com/HXo_rwK4HONJDfYw73IF1ISRmqC1hrNFxsJa8_X040E6i5VF1-7efUFRVfTwspSc53a2NA=s147)

*Student*: Iván Josa

Liquid Galaxy needed a bluetooth scanner which will interact with Physical Web (PW) Beacon. Once the scanner has found this PW beacon it will interact with the Liquid Galaxy (LG) to make it know there is someone who wants to deploy its POIs, so the LG will wait for confirmation. This LG App has an easy interface that will have a connect button, a confirmation one (for security reason). Another button was added for a restoration of the previous POIs after a visit.  

**More info**: [Bring Your Own Pois Web](https://github.com/LiquidGalaxyLAB/Liquid-Galaxy-POIs-Controller/blob/master/GSOC16.md)

* [Project Smart Coffee Machine with proximity pairing](https://github.com/alexisduque/pw-coffee-machine)

*Student*: Alexis Duque

The primary goal is to demonstrate how fun can be Physical Web and how it can make our life better, making a Physical Web enabled smart coffee machine. This coffee machine can guess your coffee preferences and brew for you a coffee as soon as you are in proximity, without you have to do anything, thanks to your personal Physical Web beacon. It can be an own machine, at home, at work, or in any public place, like a bar or a restaurant.

**More info**: [Smart Coffee Machine Web](https://github.com/alexisduque/pw-coffee-machine)

<!--
### Mentors - Who is going to help you?

* Andreu Ibañez  
Andreu is a freelancer technologist with 30 years of experience in the IT sector. Enjoying constantly innovating and creating new technologies for such diverse areas as clusters display, drones and lasers where he is currently engaged. He specializes in the ecosystem of Google, where he is mentor of Google Summer of Code with projects such as Liquid Galaxy and DC Extractor, Google Glass Explorer with Scalardrone startup, and has set up a unique laboratory in the world to do projects with various technologies where we can find Google maps integrated with the Liquid Galaxy technology. He is the founder and organizer of the Google Developers Group GDG Lleida and co-organizer of GDG in Spain, national and international speaker about new technologies and an expert on Google.
He is Chairman and Founder of Lleida Drone, association on drones  technology created in 2011. He also works as Advisor in strategy, marketing and technology in several Spanish startups, as Remotte Labs, Inc Subtix, VT-LAB and Rectangular Studios.  

* Francisco Martín-Fernández  
 received his B.Sc. degree in Computer Science at the University of La Laguna (Spain) in 2011. He is being supported by the Spain Minister under a 4 year scholarship. He is researching on security in Vehicular Ad-hoc Networks and Internet of Things. He belongs to the CryptULL research group devoted to the development of projects on cryptology. He plans to present his Thesis in 2016.  
Topics: Cryptography, Wireless Communications in Vehicular Networks, Authentication in Internet of Things, Trust Algorithms.  
He is also founder and Lead Organizer in the Google Developer Group Tenerife, from Spain.
-->

### Interested? What you have to do next...

If you want to make a proposal as student, point your browser to the [main GSoC 2017 site](https://summerofcode.withgoogle.com/) and follow the instructions there. If you need to reach us directly for any cause, contact us by [email](mailto://physicalwebproject@gmail.com).

Good Luck!

Physical Web Project GSoC Organizer and Mentors
