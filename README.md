# Ex03_LifeCycle
Lecture 01 - Basics of Android Development:  
Displays a simple message.  
The user should rotate the phone and launch other apps to force the activity to change between different states.  
These changes will be notified by messages displayed in Logcat.
- Use of Log to trace the activity's state
- React to lifecycle's callbacks
- Use of Logcat to monitor the execution of the application

Use case:
- Launch the app and check LogCat
- Press Home (the app is stopped)
- Launch the app again (the app is not created again)
- Rotate the device (emulator). Observe that the activity is destroyed and created again!
- Press back (the app is destroyed)