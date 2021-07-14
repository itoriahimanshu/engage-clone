it2Chat Application URL:
https://its2chat.herokuapp.com/

1)Authentication:

Register – > Login -> Join Room Request -> Enter room

User wont proceed unless email and password credentials match
A popup arrives as soon as either of the two fields are left empty
Logout option takes user back to the home login page
Built on npm packages :
express-flash
express-session
method-override
passport,
passport-local
Dotenv

Scope for Improvements: 
Deployment with Websockets and Webrtc features seemed tricky
Google,Microsoft,etc . credentials for registering can be integrated.


2)Chat -Room:

Enter Room -> Chat, Videocall Links, Breakout rooms links ->
          Videorooms

All Users entering the same Room id in the Enter Room credentials are grouped together.
Users can Send messages, Send user locations, Create Video Rooms for entire room and also Breakout Rooms
Breakout Rooms allow parallel meetings via which subgroups in the same group can hold sub-group conversations via videoconferencing
Foul words are prevented via “bad-words” package in npm through text messages

Built on npm packages :
Socket.io
Bad-words
Ejs
Express

Scope for Improvements: 
Notifications feature will be an excellent addition.
Upload files option would be a boon

3)Video -Room:

Enter Video Room -> Notes, Mute, Show/stop video , Share Screen
          

All Users joining with the same room id obtained from Chat room would be in same video-room.
Video-conference and Breakout Rooms allow group and parallel meetings
Notes feature will help to get the bullet points of any meet
Sharing screen in both videorooms and breakout rooms in addition to Mute and Stop video

Webrtc Apis:
getUserMedia – webcam and sound recording
getDisplayMedia- Screen sharing

Built on npm packages :
Socket.io
Peer
Uuid
Ejs
Express

Scope for Improvements: 
Captions would be great just there arent many good open-source speech-text apis, so that will be an excellent challenge
Webinar Streaming can be added without much fuss using the getUserMedia and only one client emitting responses while others are programmed to receive signals.

                   

