<!-- 
This README describes the package. If you publish this package to pub.dev,
this README's contents appear on the landing page for your package.

For information about how to write a good package README, see the guide for
[writing package pages](https://dart.dev/guides/libraries/writing-package-pages). 

For general information about developing packages, see the Dart guide for
[creating packages](https://dart.dev/guides/libraries/create-library-packages)
and the Flutter guide for
[developing packages and plugins](https://flutter.dev/developing-packages). 
-->

Contact Card Maker allows you to generate a VCARD contact card that is  compatible with iOS and Android .

## Features

Tha package generates contact card with phone , email and social media contacts.

## Getting started

The package is easy to user , install it then initalize a new Contact Card option , add the needed contacts and then call the method create to retrieve the VCard string .

## Usage

```dart
ContactCardMaker(
      {required this.name,
      this.emails,
      this.phones,
      this.whatsapp,
      this.others});
      print(cardMaker.create());
```

## Additional information
