# webRtcCommunication 

# WebRTC Project in Node.js
This README file provides an overview and instructions for setting up and running a WebRTC (Web Real-Time Communication) project using Node.js. WebRTC enables real-time audio, video, and data communication between browsers and mobile applications.

Prerequisites
Node.js (v18.16.0 prefered) and npm (Node Package Manager) should be installed on your system, Also you can use nvm to rollback or forward to use specific node version. You can download them from Node.js official website.
Getting Started
Clone the project repository or download the source code:
```
git clone git@github.com:sanketshivale/webRtcCommunication.git
```
Navigate to the project directory:
```
cd webRtcCommunication
```
Install project dependencies using npm:
```
npm install
```
Create Env file .env
and add the following details
```
PORT = 5000
DB_URL = "mongodb connection string"
```

Start the Node.js server:
```
node server.js
```
Open a web browser and navigate to http://localhost:5000.
Grant permission to access your camera and microphone when prompted.
Open another browser tab or window and navigate to the same URL.
Grant permission to access camera and microphone on the second tab as well.
You should now see the local video stream on both tabs.
Click the "Call" button on one tab to initiate a call.
The other tab will receive the call and display the remote video stream.
Enjoy the real-time video communication!
Customization
You can customize the project according to your requirements. Here are a few things you can do:

Extend the functionality in public/script.js to add additional features.
Update the signaling and communication logic in server.js as per your needs.
Contributing
Contributions to the project are welcome! If you find any issues or want to add new features, feel free to submit a pull request.

License
MIT
