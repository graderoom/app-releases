# Installation

## iOS
### iOS 12.0 and above are supported

#### All iOS devices
Use `graderoom-vX.X.X.ipa`

#### Installing
- Currently, iOS devices do not support sideloading applications by default.
- To enable sideloading applications, set up [altstore](https://altstore.io).

#### Troubleshooting
- If after a few days, the application does not open, refresh the app in Altstore

## Android
### Android 4.1 and above are supported

#### Devices with 64-bit arm CPU architecture (most common)
Use `graderoom-arm64-v8a-release-vX.X.X.apk`

#### Devices with 32-bit arm CPU architecture
Use `graderoom-armeabi-v7a-release-vX.X.X.apk`

#### Devices with x86-64 CPU architecture
Use `graderoom-x86_64-release-vX.X.X.apk`

#### Installing
- Download the .apk file compatible with your device, and open it.
- If you are prompted, allow the installation

#### Troubleshooting
- If, after opening the .apk file, you see an alert saying 'App not Installed', uninstall the current version of the app from your device and open the new .apk again.
  - WARNING: this will erase all local Graderoom settings from your device.

---

# Changelog

## [Beta M-0.1.0] - 2020-02-28
### Added
- Debug toasts can be enabled in settings
- Logo and icon buttons now respond to theme changes
- A non-functional menu button
- Loading animation while sending requests to the server
- Pull down to refresh on main screen<ul>
- Checks login status
- Gets any updated settings from the server
- Gets any new grades that may have been synced on a different device</ul>

### Improved
- Main page now contains colored cards for each course
- Main page now loads courses before sending request to sync with PowerSchool
- Changing theme is now supported
- Back button from the main screen no longer causes unintended app behavior
- Pre-load screen now displays logo and is dark themed

### Removed
- Gradient around logo

## [Beta M-0.0.4] - 2020-01-27
### Added
- Watermark over pages that don't work yet
- Light theme is back
- Temporary gradient near logo to make it always visible

### Improved
- Login screen is now bypassed if valid cookie is stored on app open
- This cookie persists through app closes and will allow automatic logins within a 4 hour period
- App now connects to https://beta.graderoom.me/

## [Beta M-0.0.3] - 2020-01-22
### Added
- Grades can now be viewed on the main screen
- This grid currently displays class names, overall grades, and overall letter grades

### Improved
- Login and signup now allow moving through fields with the mobile keyboard
- Database now clears correctly when syncing new data

## [Beta M-0.0.2] - 2020-01-20
### Added
- Offline storage allows viewing grades when PowerSchool is down

### Removed
- Temporarily removed light theme due to conflicts with icon

## [Beta M-0.0.1] - 2020-01-03
### Added
- Settings screen
- Empty forgot-password screen
- Functioning login and logout
- Logout can be accessed in settings

### Improved
- Font
- You now stay logged in as long as your session persists (4 hours)

## [Beta M-0.0.0] - 2020-12-28
### Added
- First commit
- Basic login page
- Basic themes
