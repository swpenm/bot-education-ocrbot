# First Lab

> On Windows, Mac and Unix, the instructions are pretty much the same (exceptions include:  command terminal program, adding to the system PATH variable, and other setup items).

## Prerequisites

Fufill those listed on this wiki here:  https://github.com/michhar/bot-education/wiki/Conference-Syllabus#prerequisites-for-hands-on-labs

## Setup

### Cognitive Services trial keys

To sign up for the Computer Vision trial, follow these instructions:

1.  Go to https://www.microsoft.com/cognitive-services/en-us/apis
*  Click on "My account" in the upper right-hand corner to log in to Cognitive Services.
*  You will see a 'Hello' welcome page with a listing of trials from which you can request new ones.  Please select "Entity Linking", "Computer Vision" and "Text Analytics".  Read and decide if you agree to Microsoft Cognitive Services Terms and Microsoft Privacy Statement.  After agreeing, click "Subscribe" to sign up for these trials.  

You will then be able to gain access to your keys.

### Command Terminal for running node and mono

1.  Ensure that the **PATH sys variable** has node and mono 
  * on Windows, right-click the start menu and select System -> Advanced system settings -> Environment variables... and then under System variables, check the Path
2.  Test the mono and node setups to ensure they are in your path and working.  Type `mono` into the command prompt.  You should see a help message.  If the command is not found, try opening a new terminal window.  Do the same for `node`.
3.  Git clone this repository into a suitable folder on your machine
<br> `$ git clone https://github.com/michhar/bot-education-ocrbot.git`

### Visual Studio Code

2.  Copy the github repo to another folder for "local dev"


## Instructions

3.  Open the "local dev" folder in VSCode (Open Folder...)
4.  Ensure that the COMPUTER_VISION_SERVICE API_KEY in `configuration.js` has your trial key from Computer Vision obtained above.


