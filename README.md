# CORD-Android
An Android application focusing on user safety and sporting activities. 
Developed to give the user a piece of mind that if something negative should occur, a nominated person will be notified.

159.333 Personal Project 
Done by: 
    Nathaniel Fort & Sreeman Nalli

Introduction
As the developers of CORD, we required an idea for the course 159.333 at Massey University. 
As active people, we saw a need for added safety when doing sports activities, especially when alone. 
Whether it be fishing off rocks, going on a hike or mountain bike track, or even something as simple as walking a dog, the benefits of know if something were to go wrong that someone will be notified and help is on the way. 
This is where the idea behind CORD was born.

Application Description
CORD was developed with the main function focusing on the user’s safety and a detailed selection of sports activities as a secondary function. 
To address the safety aspect of the application, the user can ‘Check-in’ before starting an activity and states an estimated time the activity will take. 
If the user has not checked back in by the end of the estimated time, then a warning is sent to the user itself and a nominated person stating that the user has failed to return from the activity. 
The user can nominate another user of the application to receive a push notification, give a contact number for a next of kin to receive a SMS (not currently implemented), or give an email address for someone to contact. 
If the user has given all three, all the methods will be used. 
Adding to the safety aspect is knowing the last location of the user. 
This is achieved by storing co-ordinates of the user’s location while there is a current activity. 
The user’s location is ‘pinged’ and stored in the CORD database, this location can be used to help locate a missing user. 
The secondary feature of the app allows a user to find activities that are ‘near-me’. 
These activities can be generated from other users who have saved past activities.
As an example, a user who mountain bikes can chose to store a completed activity. 
Other users can select the ‘near-me’ feature and view saved activities near the user’s location, that match the users sport preferences (not currently implemented). 
Combined with this the user will also see activities, based on their preference, that Google has located near their location.

Current features of the application
The features listed below are the currently implemented in the application.
• Allows a new user to register with their email address to use the app
• Allows existing users to log-in, using their ‘username’ and ‘password’
• Prompts a new user to setup their account by selecting their sports preferences
• Displays a list of activities from the database based on the user’s sports preferences
• Allows users start an activity and estimate the end time
• Allows the user to view current information about an active activity, like its end time, the person to notify and so on.
• Allows the user to extend the end time of an ongoing activity numerous times
• Allows users to update their personal details like, Name, Mobile Number and email address
• Allows the user to end an activity before its estimated end time
• Allows the user to add a person to notify, which is set to NULL by default, when a new user registers.