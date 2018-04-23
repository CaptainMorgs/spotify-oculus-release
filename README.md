# spotify-oculus-release

Unity project for interacting with Spotify in virtual reality for the Oculus Rift.

![alt text](https://i.imgur.com/ZP7kIFR.jpg)

# Set up
Enable "Unkown sources" in the oculus destop app in Settings -> General.
Have the data folder in the same folder as the .exe and launch.

# instructions
Your browser will be opened for you to sign in to your Spotify account.

There will be no Spotify data on first launch so hit the "Reload" button on the UI on your left hand (see trailer if you are having trouble finding it). It will take approx 2 mins to load.

Spotify data is saved at the location of your devices application persistant data path as specified here https://docs.unity3d.com/ScriptReference/Application-persistentDataPath.html 

Example of location

![alt text](https://i.imgur.com/Fp2UdnN.png)


If songs are not playing, play a song on your Spotify client, an active device must be present for songs to play.
