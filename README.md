This app has been developed as part of the academic project (group project).  It has been developed to automate the regular manual attendance system.

Features of the App: Security, performance ( Volley library has been used to respond to multiple HTTP requests ). Do look at the presentation for the concept of the app.

The Workflow of the app is as follows:
1. The student registers to our app.
2. Login to the app.
3. The App asks the user whether he/she wants to receive updates/notifications from the administration and he/she starts receiving notifications as per his/her choice made here.
4. User clicks on 'Update his attendance' as he/she is present in the class. Now the app requests the fingerprint of the user. If the fingerprint is verified, then the app checks the GPS location of the phone ( latitude, longitude, and altitude ) and if it's within the bound of the classroom, then he/she gets marked present or absent depending on the location of his phone. This attendance further gets updated in the database.
5. A separate web page is created for the faculty so that they can send the notifications to the specified user using the google firebase.

Disadvantage: Accuracy is the main measure. As GPS system is going on improving with time, we think that our app works perfectly fine in future. But as of now, there is a need to maintain a little bit of tolerance between the classroom and benches.
Note: Please do download the app_demo.mo4 file to view the demo. 
