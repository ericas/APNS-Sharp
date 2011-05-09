Apple Push Notification & Feedback Services Client C# Library
=============================================================

A free, open source, independent and mono compatible C#/.NET Library for interacting with Apple's Push Notification & Feedback Services for the iPhone/iPod.

##News
 + **May 9, 2011** Moved project to Github!
 + **March 27, 2010** Updated to 1.0.3.0 with a couple bug fixes
 + **January 18, 2010** Added a very simple sample solution for MonoTouch that shows how implement Push Notifications in a MonoTouch? application
 + **December 22, 2009** [Apns-Sharp now Powering G-Push Mail](http://redth.info/2009/12/22/apns-sharp-updated-and-now-powering-g-push-mail/) (New Version: 1.0.2.0)

##Features
 + Push Notifications Client
 + Feedback Service Client
 + iTunes Receipt Verification Client

##Details
This is a pretty simplistic library, but it should give all C# developers a jump start into developing for Apple's Push Notifications platform. Feel free to use it as needed.

One of the goals was to make this mono compatible, since I needed it myself to run on Debian/Mono 2.4 on Amazon's EC2 Platform. This works great on mono 2.4, I have not tested it on anything below 2.4.

I have also included a simple iTunes/AppStore Receipt Verification Library that simplifies the process for verifying the receipt data from In-App Purchases.

##Testing
The code for the Apns Notifications is fairly well tested and currently in use in a production app. The code for the Feedback service should be ok, however I'm working on integrating it into my production app at this point. The AppStore? code is the least tested of all, please report any bugs you run into with this!

I would encourage you to checkout the source and use that! Please use this project page's issue tracker to send me bugs, and I will fix them!

##Contributing
If you have improvements to my code, by all means let me know. If you'd like to become a contributer to the project, I'd be happy to make that happen too!