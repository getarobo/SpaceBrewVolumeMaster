# SpaceBrewVolumeMaster
Master Volume Controller using spacebrew
By: Getarobo and David Cihelna

A web application that allows a master user to control the playback and volume of HTML 5 audio on an unlimited number of clients. Runs using a standard Spacebrew node server. Run the server and serve these files. Then connect to that port on your localhost and /master.html or /music.html

For example, we loaded multiple stems of the same track (Nine Inch Nails). When clients connected, Spacebrew automatically connected them using persistence methods. Then the master could play/pause and choose the individual volumes of each stem as they played in realtime. There was no lag.

Made at ITP with the help of Brett Renfer from Spacebrew
