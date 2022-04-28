# Fultter-Demo
Flutter Demo Application with everything working in IntelliJ 2022

## To get everything working:

### Download Flutter SDK
The Flutter SDK can be found on the Flutter website.
After downloading it, run the flutter console.
Within the consol, run the flutter doctor command. It will show you what other components are required.
We will not be needing to install Android Studio. Instead, IntelliJ will be used

### Install Visual Studio
I installed Visual Studio Pro 2022 v17 will all build tools (~30GB). Flutter only required the Desktop development with C++.
Take note of the exact Windows SDK required by Flutter using flutter doctor from the Flutter console.

### Download Android SDK
Create an Android project in IntelliJ.
Once created, go to File > Project Structure. Therein, select the SDK drop-down and select Add SDK. Use this to download the SDKs required.

### Create a Flutter application
Using IntelliJ, on the welcome screen (ie when all projects are closed), select Plugins. Select Marketplace. Search and install Flutter. Restart IDE.
Create a Flutter demo application.

### Copy a file
For this application, I had to copy a certain file in order for the Windows application to work.
Copy build/windows/app.so to build/windows/runner/Debug/data/app.so.

### Open Android part of the app
In Project view mode on the right-hand pane, right-click the Android part of the application and select Open In > Explorer.
Once there, open that directory as a project in IntelliJ.
From here, you can install all the necesary Android components or point to the downloaded SDK. You can also select Tool > Android > AVD Manger to add an emulator.
Close this when done.

-------------------------------------------

This is not an exhastive list of things to do but it does capture some of the important stuff.
