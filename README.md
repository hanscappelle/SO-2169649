# SO-2169649

Answer to the SO question at http://stackoverflow.com/questions/2169649/get-pick-an-image-from-androids-built-in-gallery-app-programmatically/2636538

    I am trying to open an image / picture in the Gallery built-in app from inside my application.
    I have a URI of the picture (the picture is located on the SD card).
    Do you have any suggestions?

## Getting started

Clone this project on your system and use Android studio to import this project using menu options:

    File > New Project > Import Project

## Required permissions

Don't forget to update the permissions of your app if you want file selection from SD card to work

    <uses-permission android:name="android.permission.READ_EXTERNAL_STORAGE" />

## Credits

The UserPicture class was originally implemented by user @hdante that I just converted to a utility
class. For his profile on stackoverflow check this link: http://stackoverflow.com/users/1797000/hdante

## TODO

* review the UserPicture class into a static utility class
* fix the multiple image selection