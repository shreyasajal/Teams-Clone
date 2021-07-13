
# Teams-Clone
The project has been built with React.I have used WebRTC implementation for
direct calls and PeerJs( (library to make WebRTC implementation easier in small apps) for
group calls. I have used Socket.IO as the signaling server for the application.
Our application uses: WebRTC, JavaScript, Socket.IO, Express.js, Node.js, React,
Redux
Deployed Project Link:https://teams-front.herokuapp.com/
Documentation:https://drive.google.com/file/d/1tJWUOQ6dbS_3Jd8QsM_xdmx3fmMd5ZAC/view?usp=sharing
Reference Videos Links:
* https://www.youtube.com/watch?v=XWL_Rzqk4CY
* https://www.youtube.com/watch?v=DvlyzDZDEq4
* Playlist:https://www.youtube.com/watch?v=h2WkZ0h0-Rc&list=PL_YW-znSZ_dK365WaVuiBUN6FYc9_1hni

While running the code locally :
* One can use their turn server credentials from Twilio (free) to generate the token and use in Backend/server.js- app.get in accountSid and authToken.(Sharing my authtoken publically revokes the token and stops the deployed app to avoid fraud)
![Screenshot (229)](https://user-images.githubusercontent.com/58565264/125498287-15220789-72a8-4b8f-9c79-7e7683d1e21d.png)

* Change the server as const SERVER = 'http://localhost:5000'; in wssConnection.js file in frontend/src/utils
* Change the axios.get code to axios.get("https://localhost:5000/api/get-turn-credentials") in Dashboard.js in frontend/src/Dashboard 

# Project Directory structure
![Screenshot (227)](https://user-images.githubusercontent.com/58565264/125444933-6de2acf5-113a-4c70-8a3b-dab27e127d26.png)
