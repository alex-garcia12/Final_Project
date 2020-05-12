# Final_Project
Final project for CPSC 411

Moustapha Said 888907524
Alex Garcia 802297556
Ruiwen Zhang 887649846

This is our sound recorder app for the final project of CPSC 411. 
- Press the Start button to start recording. 
- Press the Pause button to pause the current recording.
- Press the Stop button button to end all recording.
- To listen to your recording, you must navigate to your device's storage:
Settings -> Storage -> Files -> [recording.mp3 should be at or near the bottom of your storage]

----------------
Things to note:
---------------------------------------------------------------------------------------------------------------------
- This app works fine on both an emulator and on physical devices. However, we could not figure out how to get
  audio recorded on the emulator. In order to use this app to its fullest, we ask that you use a physical device
  to use and test the sound recorder. 

- The app should ask you for file access and microphone permissions. These permissions are needed to properly use
  the app. 

- If the app for some reason does not ask you for these permissions, go into your device's 
  Settings -> Apps (& Notifications) -> Final_Project -> Permissions. From there, turn on permissions for Microphone
  and Storage. The app should work now. 

- The app can record only one "session" at a time. When first opening the app, you can start recording, pause, resume,
  and stop with no problem. However, when trying to record again in the same session, the Start button doesn't work
  again for some reason. To make another recording, you'll have to completely close the app and open it again. 
---------------------------------------------------------------------------------------------------------------------

Project:
---------------------------------------------------------------------------------------------------------------------
- We tried to implement a ViewModel component to allow for things like configuration changes but we could not figure
  it out and we ran out of time.

- We also tried to implement a directory of sorts to allow for multiple recordings (not just overwriting the same
  'recording.mp3' file multiple times) but could not get it to work
