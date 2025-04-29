# firebase_assignment10

# Assignment Week 10


You are tasked with creating a mini social feed app. The app should allow users to:
Register/Login


Post messages to a public feed


View all messages from Firestore


Receive updates through FCM


Change app behavior using Remote Config (like toggling dark mode or enabling/disabling post feature)

Modules to Implement
Firebase Authentication


Implement email/password sign-up, login, and logout.


Store and display the user's name after registration.


Cloud Firestore


Create a Firestore collection named posts.


Each post should include: message, userId, timestamp, and username.


Display all posts in reverse chronological order.


Only authenticated users can add posts.


Remote Config


Add a boolean parameter isPostingEnabled.


If set to false, hide the post input field and show a message like "Posting is currently disabled".


Use default values in code and allow overrides via Firebase Console.


Firebase Cloud Messaging (FCM)


Set up FCM to receive push notifications.


When a new post is added, send a notification to all users:
"New post by [username]: [first 10 words of the message]".


App Distribution


Generate a release build (APK).


Distribute the app using Firebase App Distribution.


Share it with at least one tester for feedback.




