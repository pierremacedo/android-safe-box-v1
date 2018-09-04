# Android Safe Box
NOTE: No apk file will be provided for the version 1 (v1) of this app due to slow performance. The combination of the NativeScript framework plus the SQLite database produced an application with slow performance when saving and deleting data. To get a fast version built with React Native and Realm, go here https://github.com/pierremacedo/android-safe-box-v2

This app as its name implies is a place to store sensitive information such as bank accounts, credit cards, personal documents, etc., on android devices. 
## Security
The SQLCipher database used in this project encrypts its data with 256-bit AES. The encryption method consists of generating a strong key from a ten characters password provided by the user. Neither the user's password nor the encryption key are stored on the device permanently. The key is temporally stored on the device using this secure module created by myself https://github.com/pierremacedo/nativescript-temporary-key-storage.

## Screenshots
<p align="center">
<img src="https://raw.githubusercontent.com/pierremacedo/android-safe-box-v1/master/screenshots/splashscreen.png" height="350" title="splash screen">
<img src="https://raw.githubusercontent.com/pierremacedo/android-safe-box-v1/master/screenshots/registerscreen.png" height="350" title="register screen">
<img src="https://raw.githubusercontent.com/pierremacedo/android-safe-box-v1/master/screenshots/loginscreen.png" height="350" title="login screen">  
<img src="https://raw.githubusercontent.com/pierremacedo/android-safe-box-v1/master/screenshots/mainscreen.png" height="350" title="main screen">  
</p>
