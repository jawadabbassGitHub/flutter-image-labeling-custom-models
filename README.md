# 📸 Flutter Image Labeling App

A Flutter app that detects and labels objects in images using **Google ML Kit**.  
Users can either **capture** an image using their camera or **select** one from the gallery, and the app will analyze the image and display object labels with confidence scores.

## 📝 Description

This app leverages **Google ML Kit’s Image Labeling API** to recognize objects in images.  
It provides an intuitive UI where users can:
- **Take a picture** with the camera or **choose an image** from the gallery.
- **View detected objects** along with their confidence levels.
- Experience a **modern and responsive UI** with smooth interactions.

This is a great starter project for developers looking to integrate **machine learning** into their Flutter apps! 🚀

## 📦 Dependencies

Run the following command to install required packages:

```sh
flutter pub add image_picker google_mlkit_image_labeling path_provider path

🚀 Running the App
For Android Emulator or Device
Make sure you have Android Studio installed with an emulator or a physical device connected.

Run:

flutter run

For iOS Emulator
Install CocoaPods dependencies:
cd ios
pod install
cd ..
Open the project in Xcode and set up an iOS simulator.
Run:
flutter run
📝 Notes
Ensure that your Android device/emulator has Google Play Services.
On iOS, add the required permissions in ios/Runner/Info.plist:

<key>NSCameraUsageDescription</key>
<string>We need camera access for image recognition</string>
<key>NSPhotoLibraryUsageDescription</key>
<string>We need gallery access for image selection</string>

📸 Features
Pick images from Gallery or Camera.

Detect objects using Google ML Kit.

Display labels with confidence scores.

Modern UI with smooth animations.

