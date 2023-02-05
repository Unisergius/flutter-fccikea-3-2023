# Intro To Flutter - fccAlgarve
## _A brief look into Dart and Flutter_

This meetup will be based on the first Flutter Faro meet in 2022, a Flutter instalation party. 

Subjects:

- Install Flutter 
- Create your first app
- Watch it work on a browser
- Connect it to an API
- Further Flutter events with Flutter Faro and GDG Faro

## Install Flutter SDK

We'll start with the SDK. Installing and preparing our system to work
with Flutter. The following link will lead you to what you need to install it.

- https://docs.flutter.dev/get-started/install

Follow the instructions carefully. Make sure you add your flutter tool to your environmental path so the operating system can find flutter's location. 

- Windows - https://docs.flutter.dev/get-started/install/windows#update-your-path
- Linux - https://docs.flutter.dev/get-started/install/linux#update-your-path
- MacOs - https://docs.flutter.dev/get-started/install/macos#update-your-path

If you already have Flutter SDK installed, upgrade it with the following command. The version we're going for is Flutter 3.7 which is the latest version by the time this event is happening. Flutter 3.7 was announced at Flutter Forward event in January.

- https://docs.flutter.dev/whats-new

```sh 
    flutter upgrade
```

Run Flutter Doctor to check if everything is setup correctly.

```
    flutter doctor
```

This instruction will display information about whether your personal computer has everything you need to build flutter apps to all the platforms. We'll focus on web apps for today. 

For web apps, you'll need a browser. Flutter will display a warning if you don't have Google Chrome installed but you can technically use any browser for it to work. If there's something complicating your progress and you're okay with installing Google Chrome, then please do it. 

If everything is working, we are ready for our next step. 

# Our First App

We'll follow instruction from the flutter codelab 'your first Flutter app'.

- https://codelabs.developers.google.com/codelabs/flutter-codelab-first

This is a nice start for Flutter. All the necessary steps are here. 

- Create a Project
- Understand Widgets
-- Stateless Widgets
-- Stateful Widgtes
- Add functionality

After this you'll get a basic idea how structuring an app in flutter feels like. If we still have time, we are going to try and follow another codelabs page. Here are some options

- https://codelabs.developers.google.com/codelabs/flutter-flame-game ( 1h30m )
- https://codelabs.developers.google.com/codelabs/google-maps-in-flutter ( 30m )

# Flutter 3.7 - Flutter Forward 

- A ton of new widgets from Material 3 - https://flutter.github.io/samples/web/material_3_demo/
- Improved performance on IOS apps - Impeller preview
- Desktop global menu bars on Mac 
- Tests to validate your application before you upload it on the IOS app store. Will check all the necessary requirements. 


# Flutter Faro Event: Flutter + ChatGPT

- 16th February
- Ualg Tec Campus, 2nd Floor
- We'll learn how to interact with ChatGPT API in our Flutter application

