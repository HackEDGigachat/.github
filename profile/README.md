# Hi there. Welcome to our Home Page

This is where we put all of our cool projects. I hope you enjoy our tour around our github.:smile:.

<div id="header" align="center">
  <img src="http://www.reactiongifs.com/r/cheering_minions.gif" width="1000"/>
</div>


# What is GigaChat?

GigaChat is an organization trying to create a voice base virtual assistent

# What is the problem?

With the increase in a variety of technology, many people have access to services such as IoT(internet of things), and applications. Technology helps improve people's productivity by organizing their ideas, making data use convenient, and accelerating our learning. 

One of the problems to consider are when people have trouble communicating with services effectively. With the help of a virtual assistant using voice, it will allow for easier use between the user and the service. For people who don't struggle with using technology, using voice can be another great option over the alternatives such as writing, typing, and drawing.

#### Master diagram:

<div id="header" align="center">
  <img src="https://github.com/HackEDGigachat/.github/blob/main/profile/assets/GIGACHAT-masterDesign.png" width="1000"/>
</div>

The master diagram consists of 2 systems of I/O. The first type uses speech, and the second uses typing. Speech input will be automatically converted to text and sent through our database. The message processes through a sniffler, choosing one of the services we provide. Some services will be through the openAI, while looking up time or weather uses the google search API. 

#### Our UML

<div id="header" align="center">
  <img src="https://github.com/HackEDGigachat/.github/blob/main/profile/assets/GIGACHAT-UML.png" width="1000"/>
</div>

We only have 2 classes that are stored in the database. The message contains all the message details to link to the user, and sort by timestamp. The user consists of the username and password.

#### Website Storyboard:

<div id="header" align="center">
  <img src="https://github.com/HackEDGigachat/.github/blob/main/profile/assets/GIGACHAT-StoryBoard.png" width="1000"/>
</div>

For the website, there consists of 2 pages, where the first is the login page, and the 2nd is the list of messages sent and recieved

#### Our fLowchart for the Pi

<div id="header" align="center">
  <img src="https://github.com/HackEDGigachat/.github/blob/main/profile/assets/GIGACHAT-RasberryPiFC.png" width="1000"/>
</div>

This is a more detailed flowchart for the left side of the master flowchart. The system listens for a prompt to be heard. Once the promt is heard, it records the next prompt to be processed through the database. The response is sent back in the form of sound.

#### Library Hierarchy

<div id="header" align="center">
  <img src="https://github.com/HackEDGigachat/.github/blob/main/profile/assets/GIGACHAT-HierarchyDiagram.png" width="1000"/>
</div>

Here is the list of packages created for controlling the database, api services and sniffler.

#### Coding Languages used:
<div>
  <img src="https://github.com/devicons/devicon/blob/master/icons/react/react-original-wordmark.svg" title="React" alt="React" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/css3/css3-plain-wordmark.svg"  title="CSS3" alt="CSS" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/html5/html5-original.svg" title="HTML5" alt="HTML" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/javascript/javascript-original.svg" title="JavaScript" alt="JavaScript" width="40"height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/python/python-original.svg" title="Python" alt="Python" width="40"height="40"/>&nbsp;
</div>
