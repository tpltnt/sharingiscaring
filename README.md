__about__

Sharingiscaring allows you to instantly share files in a peer-to-peer fashion from your browser.
As long a you keep the window open, the file is available to everyone who knows the link. As 
soon as you close it, the file is gone. Nothing is stored on the server.

__installation__

    npm install

__usage__

    node server.js

The default port is 8000. It can be changed by setting process.env.PORT:
* temporarely: ```$ PORT=1234 node server.js```
* permanently: ```$ export PORT=1234; node server.js```