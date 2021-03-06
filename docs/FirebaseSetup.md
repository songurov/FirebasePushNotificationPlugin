## Firebase Setup

1. Login to https://console.firebase.google.com and create a new project

![Creating Project](https://github.com/CrossGeeks/FirebasePushNotificationPlugin/blob/master/images/firebase-portal-create-project.png?raw=true)


2. After project is created you should see options to add Firebase to your iOS and Android apps

![Firebase Overview](https://github.com/CrossGeeks/FirebasePushNotificationPlugin/blob/master/images/firebase-overview.png?raw=true)

#### Android Firebase Setup

3. Let's start adding firebase to our Android application. Package name must match your Android app package name.

![Add Firebase to Android](https://github.com/CrossGeeks/FirebasePushNotificationPlugin/blob/master/images/firebase-portal-create-android-app.png?raw=true)

4. Download the file google-services.json

![GooglePlayJson](https://github.com/CrossGeeks/FirebasePushNotificationPlugin/blob/master/images/firebase-portal-android-json.png?raw=true)


#### iOS Firebase Setup

1. Add Firebase to iOS App. Bundle identifier must match your iOS app bundle identifier.

![Add Firebase to iOS](https://github.com/CrossGeeks/FirebasePushNotificationPlugin/blob/master/images/firebase-portal-add-ios-app.png?raw=true)

![Add Firebase to iOS](https://github.com/CrossGeeks/FirebasePushNotificationPlugin/blob/master/images/firebase-portal-create-ios-app.png?raw=true)

2. Download GoogleService-Info.plist

![Plist iOS](https://github.com/CrossGeeks/FirebasePushNotificationPlugin/blob/master/images/firebase-portal-ios-plist.png?raw=true)

![Apps added](https://github.com/CrossGeeks/FirebasePushNotificationPlugin/blob/master/images/firebase-portal-apps.png?raw=true)

3. Configure APNs with FCM: https://firebase.google.com/docs/cloud-messaging/ios/certs

4. Upload iOS TLS certificate/auth token on Settings -> Cloud Messaging section:

![Certificate](https://github.com/CrossGeeks/FirebasePushNotificationPlugin/blob/master/images/firebase-portal-ios-certificate-0.png?raw=true)

![Certificate](https://github.com/CrossGeeks/FirebasePushNotificationPlugin/blob/master/images/firebase-portal-ios-certificate.png?raw=true)

<= Back to [Table of Contents](../README.md)
