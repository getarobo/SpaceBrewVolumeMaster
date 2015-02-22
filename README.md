# SpaceBrewVolumeMaster
Master Volume Controller using spacebrew
By: Getarobo and David Cihelna

A web application that allows a master user to control the playback and volume of HTML 5 audio on an unlimited number of clients. Runs using a standard Spacebrew node server.*

*Get the server from here: https://github.com/Spacebrew/spacebrew

Important Notes: 
1. You need to go into the code of both these files and alter sb.server = "104.131.48.13"; (line 34 or 29) to your IP. 

2. Load your own .mp3 files into music.html (line 94). 

3. Run node_server_forever.js in terminal.
 
4. Connect to your IP/localhost and port, then request /index.html (controller) or /music.html (client).
 
5. Open Spacebrew admin from the admin folder (its the index.html file) of the server folder to config the routes.

For example, we loaded multiple stems of the same track (Nine Inch Nails). When clients connected, Spacebrew automatically connected them using persistence methods. Then the master could play/pause and choose the individual volumes of each stem as they played in realtime. There was no lag.


Made at ITP with the help of Brett Renfer from Spacebrew
