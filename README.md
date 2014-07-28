ChipsLibrary for Android Studio
===============================

This is a fork of AndroidDeveloperLB's chips library shown [**here**][1]

![screenshot][3]

This is modified with gradle support for easier importing into Android Studio. Simply add the files in android studio and make sure to add the include statement in the main project's settings.gradle. 

For example *include ':libraries:chips'*

- Added permanent hint support. Use the setHint("hint") method on the RecipientEditTextView to have it remain there and chips/text will be placed after it. Note, must remove one of the focus change options.
`view.setHint("Hint");`

















  [1]: https://github.com/AndroidDeveloperLB/ChipsLibrary
  [3]: https://lh3.googleusercontent.com/-0tiDXRdjE9w/UEKSRdUaS6I/AAAAAAAAoqw/thtcKMWSWKs/w393-h683-no/png.png
