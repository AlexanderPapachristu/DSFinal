**********Activate the server**********
1. Download and extract the files to any destination on your computer.
2. Open up the command prompt in the folder location and run the command "npm i" to download all libraries in the package.json
3. Run "npm run start" to start the server.

**********Start the OBS stream**********
1. Download OBS from the website listed: https://obsproject.com/download
2. Open settings on the bottom right side of the application and navigate to stream tab
3. Change settings to the following:
       Service: Custom
       Server: rtmp://213.255.209.79/show
       Stream Key: test
4. Set up a video to be playing for the stream by adding a new source and choosing "media source" from the list prompted
5. Press start streaming and OBS should connect to the server as indicated by a green square in the bottom right of the window.

*********Open the website*********
1. Open up your browser of choice
2. Type into the url bar "localhost:3000"
