# blogapp

## GoogleDrive Folder for Video and release mode apk:

https://drive.google.com/drive/folders/1wi5tWh8f8lKwWjO6OhGFiKJxPj4Wd5kU?usp=sharing

----------------------------------------------------------------------------------------------------------------------------
## Setup for the App:

-lib\config\firebasecreds.dart :

class FirebaseCredentials {
  static const String apiKey = 'YOUR_API_KEY';
  static const String appId = 'APP_ID';
  static const String messagingSenderId = 'MESSAGING_SENDER_ID';
  static const String projectId = 'PROJECTID';
  static const String storageBucket = 'STORAGE_BUCKET';
  static const String iosBundleId = 'IOS_BUNDLE_ID';
}



-android\app\google-services.json :
ADD YOUR GOOGLE_SERVICES.JSON FILE IN THE ABOVE PATH
----------------------------------------------------------------------------------------------------------------------------



After installing app, you have to enable OpenByDefault setting to enable deepLink working.
Follow these steps

![image](https://github.com/Mr-CodeBin/blogappassign/assets/109690866/49b60fd8-ad3d-4083-b02f-55ede2458b2e)

![image](https://github.com/Mr-CodeBin/blogappassign/assets/109690866/23831c25-9f36-42a1-8f7b-87a3cd02d493)

![image](https://github.com/Mr-CodeBin/blogappassign/assets/109690866/9208252d-76e9-4afd-8b24-3a9d5d4c384a)




----------------------------------------------------------------------------------------------------------------------------
##  DeepLink Testing Link:

https://www.test-blog-app.com/blogs?id=05047e58-7093-4450-b434-e7d28c2f66e8

Note:
You can long press to copy the deeplink of a specific blog to test the working.


----------------------------------------------------------------------------------------------------------------------------
----------------------------------------------------------------------------------------------------------------------------
A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
