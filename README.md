# flutter_first_app

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.


## Describtion of the application.

The application generates cool-sounding names, such "newstay", "lightstream", "manbrain", or "graypine".The user can ask for the next name, favorite the current one, and reviewed the list of the favorite names on a seprate. The app is responsive to different screen sizes.

## What you'll learn.
    * The basic of how Flutter works>
    * Creating layouts in Flutter.
    * Connecting user interactions (like bottom presses) to app behavior.
    * Keeping your Flutter code organized.
    * Making your app responsive (for different screens)
    * Achieving a consistent look & feel of your app.

## Add bottom :
    ElevatedButton(
              onPressed: () {
                print('button pressed');
              },
              child: Text('Next'),
    ),

## Tips :
    LayoutBuilder permet de modifier l'aboreescence des widgets en fonction de l'espace disponoble.

    Pour iterer une collection :
        messages.map((m) => Text(m)).toList()