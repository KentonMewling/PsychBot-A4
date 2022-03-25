# Psych Bot

### Navigation
- [Project Setup](#project-setup)
- [Project Description](#project-description)
- [Project Documentation](#project-documentation)
- [Unit Tests](#unit-tests)
- [Features by Branch](#features-by-branch)
- [Dialogue](#dialogue)
- [Assignment 3 New Features](#assignment-3-new-features)
- [Data Flow Diagrams](#data-flow-diagrams)
- [Project Demo](#project-demo)
- [Contributors](#contributors)
- [Presentation](#presentation)

## Project Setup

***Pre-requisites*** - Install the latest version of Python on your computer (Python3 is strongly recommended),
and the package management system (PIP).
After cloning the repository to your computer, follow these steps to launch the program:

**Step 1:** Open the repository in your IDE ([Visual Studio Code](https://visualstudio.microsoft.com/vs/) is recommended).  
&nbsp;  
### **For Windows**  
&nbsp;

**Step 2:** Open your Powershell command line tool.

**Step 3:** Create a virtual environment by running the following command:

```bash
python -m venv venv 
```
**Step 4:** Run a virtual environment by running the following command:
```bash
 ./venv/Scripts/activate.ps1
```
**Step 5:** Run the following to command to install all necessary dependecies:
```bash
pip install -r requirements.txt
```  
**Step 6:** Start the program by running this command:
```bash
python app.py
```
&nbsp; 

### **For Unix Based Systems**  
&nbsp;  
**Step 2:** Open a terminal in your VSCode by going to ***Terminal > New Terminal***  
**Step 3:** Run the following to command to install all necessary dependecies:
```bash
pip install -r requirements.txt
```  
**Step 4:** Start the program by running this command:
```bash
python3 app.py
```
&nbsp; 

## Project Description
The project was created for the UBC Okanagan third year level course.

**Psych Bot's** goal is to give the user psychological advice*. This bot serves as an interactive conversational agent that takes the user's input (a sentence) and outputs an appropriate response. As this assignment does not require Machine Learning implementation, the chatbot may provide a reply that may not relate to the user's prompt.


*For **legal** reasons, neither the bot nor developers are certified to provide medical help.


## Project Documentation
- [Project Plan Document](https://github.com/KentonMewling/Psych-Bot/blob/main/docs/Assignment2_Project_Plan.pdf)
- [Word Breakdown Structure](https://github.com/KentonMewling/Psych-Bot/blob/main/docs/WBS.png)
- [Gantt Chart](https://github.com/KentonMewling/Psych-Bot/blob/main/docs/Gantt%20Chart.png)
- [Network Graph/Branch & Commits](https://github.com/KentonMewling/Psych-Bot/network)
- [Unit Test Documentation](https://github.com/KentonMewling/Psych-Bot/blob/main/docs/UnitTesting_documentation.pdf)
- [API Documentation](docs/API.pdf)

## Unit Tests

### **For Windows**
&nbsp;

**Step 1:** Open your Powershell command line tool.

**Step 2:** To run the unit test in the Bot class run this command:
```bash
python tests/bot.test.py 
```
**Step 3:** To run the unit test in the FileReader class run this command:
```bash
python tests/fileReader.test.py
```
&nbsp;
### **For Unix Based Systems**
&nbsp;

**Step 1:** Open a terminal in your VSCode by going to ***Terminal > New Terminal*** 

**Step 2:** To run the unit test in the Bot class run this command:
```bash
python3 tests/bot.test.py
```
**Step 3:** To run the unit test in the FileReader class run this command:
```bash
python3 tests/fileReader.test.py
```
&nbsp;
## Features by Branch

<img src="./docs/images/newgraph.PNG" width="850" >

## Dialogue

## Assignment 4 New Features

### Google Translate API ###
 
 <img src="./docs/images/GUI.PNG" width="300" height="500">

### Synonym Recognition ###

**>The bot is able to understand the users language and respond in the langauge of the user, using googletrans API**

<table>
  <tr>
     <td>Word : English</td>
     <td>Word : Finnish</td>
     <td>Word : Chinese</td>
  </tr>
  <tr>
    <td><img src="./docs/images/engl.png" width="300" height="500"></td>
    <td><img src="./docs/images/finnish.png" width="300" height="500"></td>
   <td><img src="./docs/images/chinese.png" width="300" height="500"></td>
  </tr>
 </table>
 
 ### Wikipedia API ###
 
 **>User can interact with the bot and get information directly from wikipedia based off of the users input**
 
 <table>
  <tr>
    <td>English Link to a Wikipedia page</td>
  </tr>
  <tr>
    <td><img src="./docs/images/engLink.png" width="300" height="500"></td>
  </tr>
 </table>
 
 ### Sentiment Analysis ###
 
 **>the program determines if the user's response has a positive or negative context**
 
 <table>
  <tr>
    <td>Negative</td>
    <td>Positive</td>
  </tr>
  <tr>
    <td><img src="./docs/images/SA1.PNG" width="300" height="500"></td>
    <td><img src="./docs/images/SA2.PNG" width="300" height="500"></td>
  </tr>
 </table>
 
 ## Data Flow Diagrams ##
 
 ### Data Flow Diagram level 0 ###

This is a level 0 data flow diagram. It shows the abstract relationships between the user, our graphical user inferface and the bot interact. 

<img src="./docs/images/DFD0updated.png" width="1000">
 
 ### Data Flow Diagram level 1 ###


This is a level 1 data flow diagram. It shows a more specific relationship between the user, our graphical user inferface and the bot. This includes the process in which the bot recieves data from the GUI, processes that data through the Porterstemmer as well as many language toolkits to improve the response.

<img src="./docs/images/DFD1updated.png" width="1000">

## Project Demo 

**A: Sample Demo #1**

<img src="./docs/images/getLang.png" width="500">


**A2: Sample Demo #2**

<img src="./docs/images/responseTranslate.png" width="500">


**A2: Sample Demo #3**

<img src="./docs/images/transNode.png" width="500">

## Presentation 
**Assignment 4**

## Contributors
- [@KentonMewling](https://github.com/KentonMewling)

