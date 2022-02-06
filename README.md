# SMSGateway
SMS Sending and Receiving app (Android studio + MySQL + PHP)


With this application, you can use your Android device as a SMS gateway. A webserver is running and with a HTTP GET or POST request to the WebServer you can send and read SMS.

SMS Gateway on your device. Send SMS through HTTP GET requests, add users which can send SMS through a web page (and optionally limit to a set amount per month), parse incoming SMS and forward them to Email, SMS, URL based on rules! And more!

Complete tutorial is here
https://www.youtube.com/c/AtifNaseem


https://www.youtube.com/watch?v=Xb45b121px8
How to create a complete SMS Gateway app (android app)
43,656 views • Dec 20, 2018 • We will create SMS gateway app. This app will not only read all the inbox sms but also send all the sms to our MySQL database using api.

The objective of this app is to learn.

00:00:12 App Demo

00:03:05 Project at github 
https://github.com/anajetli/SMSGateway

00:04:20 Register a free site https://www.000webhost.com

00:04:45 Upload files at 000webhost.com

00:06:11 Upload database at 000webhost.com

00:06:57 Start a new android studio Android project

00:07:10 Design a simple layout

00:08:32 Start Java code

00:10:21 Method: checkPermission()

00:12:42 use permission in Manifest file

00:13:00 code: Read sms and save to mysql

00:14:50 onRequestPermissionResult override method

00:17:15 Change date format in Java

00:19:12 code: Send sms from device

00:20:53 Android Volley library implementation

00:21:25 PermissionEverywhere from github 
https://github.com/kaknazaveshtakipis...

00:21:57 Volley simple request code

00:23:46 Broadcast Receiver for reading incoming SMS

00:26:25 Register broadcast in Manifest file

00:28:00 Firebase Console https://console.firebase.google.com

00:28:35 Add firebase to app

00:31:40 Remove error firebase-messagin-15.0.0

00:32:31 Firebase message receiving class

00:33:46 Firebase web API key placement

00:37:40 use per PermissionEverywhere method in firebase messaging service

00:38:41 register firebase messaging service class as service
