# JavaScript 30 #20: speech-recognition
This is the web speech API project recognizing the user speech and converting it to text. </br>

## Installation 
Clone this repository with the following command 
```
git clone https://github.com/Kubrianity/speech-recognition.git
```
Change directory to the cloned folder
```
cd speech-recognition
```
Make sure that node and npm installed globally on your machine
```
node -v // node version installed on your machine
npm -v //  npm version installed on your machine
```
Now install project dependencies and then start with the following commands
```
npm install
npm start
```
You will be able to view the project at your server written in the command prompt </br>
http://localhost:3000 <br><br>
*Make sure that the browser is given permission to access the microphone*.<br>
### Usage & Features
Once speech is recognized, the 'result' event of Web Speech Api is fired with returning boolean value, which enables the function accessing transcript and returning it as a string.<br>
Pragraph content will be populated with speech text and with each pause, it will start with a new line.
