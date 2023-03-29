Get-Youtube-Subscribers
-----------------------
This is a node.js, express app to get the details of the Youtube Subscribers.

There are four API endpoints in this app:
-----------------------------------------
1 - "/ "

2 - "/subscribers "

3 - "/subscribers/names "

4 - "/subscribers/:id "


ENDPOINTS:
----------

1."/" default route- when app gets started this default route will render index.html file.
http://localhost:3000/

2."/subscribers"- Returns the arrays of Subscribers.
http://localhost:3000/subscribers

3."/subscribers/names"- Returns the array of Subscriber's names and subscribed channel.
http://localhost:3000/subscribers/names

4."/subscriber/:id"-Returns the array of Subcribers details which is fetched using the id given.
http://localhost:3000/subscribers/:id


LIBRARIES USED FOR THE APPLICATION:
-----------------------------------

nodemon

mongoose

mongodb

cors

dotenv

express

cross-env

morgan

supertest

SCRIPTS:
--------

npm start will start the server.

Watch Youtube video at:
------------------------
https://youtu.be/wvG92WImLms

DEPLOY:
-------
youtube-subscribers-capstone-project-22dx-7psecekwq-webdevsa.vercel.app


-----------------------------------------------------------------------------------------

Thank You.




