# Description:
Simple Zoom clone web app.

## Notes:
1. Initialize NodeJS project with npm init with ExpressJS dependencies.
2. Deploy finished project on Heroku 
### <a href="https://fast-wildwood-09704.herokuapp.com/c11f5b2b-953a-4642-b5ce-cc382c634775">LIVE DEMO<a/>

## Bugs:
1. Local audio played

***

## Client:
1. EJS (JS template engine)
- npm install ejs

2. Fontawesome (Icons eg microphone, video, etc)

3. Bootstrap (css styling)

## Backend:
1. NodeJS with ExpressJS
- npm init
- npm install express

## Server Hosting:
1. Heroku
- npm install -g heroku
- heroku create
- git push heroku master
- heroku ps:scale web=1
- heroku open

## Database:
- n/a

## Others (api, libary, framework):
1. Socket.io (asycn real time communication; allow client and server make request simultaneously)
- npm install socket.io

2. PeerJS (WebRTC libary for peer-to-peer data/communication between user, browser, apps, mobile, etc)
- npm install peer

3. UUID (to generate unique ID for unique room)
- npm install uuid
