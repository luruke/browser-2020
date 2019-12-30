It's almost 2020, and browsers can do amazing stuff.  

This repo contains a non exhaustive list of less-known features implemented in browsers **today**.

This list isn't inteded for a technical audience, instead it wants to be e a "I don't know we could that in a browser" list.

In many cases, those features aren't part of the standard yet, and only available on certain browsers / configuration only.


---

## prefers-color-scheme
Many OS provides light or dark color theme (notably dark mode on OSX), websites can detect the preferred color scheme.

---

## prefers-reduced-motion
Similarly to dark mode, users in their OS can remove/reduce animations, we can also detect that.

<img src="images/reduce.png" width="800px"/>

---

## Payment Request API
You can process payments delegating the browser. If configured, the UI will be autofilled with your credit card, shipping info and whatnot.

<img src="images/payments.png" width="300"/>
<img src="images/paymentsios.png" width="300"/>

---

## Web Share API
Delegate the share of URLs or files to the OS, providing share options based on the installed apps and user preference.

<img src="images/webshare1.png" width="600"/>
<img src="images/webshare2.png" width="300"/>

---

## Push API
Browsers can register push notifications. Sending later, at any moment push notifications, those notifications can contain images, buttons and inline replies.

<img src="images/notification.png" width="600"/>

---

## Service Workers
Among other features, service workers can enable offline browsing and background tasking.

Example:
- Provide a fallback when internet isn't available
- Sending a form when internet isn't available will result in data lost, service worker can be used to save those data and send them later when an internet connection is up again

---

## Web/native app install banners
Display a native banner to encourage users to add the app/website on the home or to install a native app.

<img src="images/banner.png" width="300"/>

---

## Get Installed Related Apps API
Check if the native app related to your site is already installed.


---

## WebXR
Allows to tun VR/AR on the web.

---

## Picture-in-Picture (PiP)
Consent to play a video and detach it from the current page, staying sticky and always visible.

<img src="images/pip.png" width="800"/>

---

## Media Session API
Customize media notifications by providing metadata and actions.


<img src="images/with-media-session.png" width="400"/>

---

## Chrome Sender API
If chromecast is available, you can stream a video/audio to your TV / Chromecast enabled device.

---

## AirPlay
Consent to stream a media over AirPlay (like AppleTV)

---

## Force Touch API
With some Apple-specific hardware (like iPhone6S+ and Magic Trackpad) you can detect force pressure.

---

## AR Quick Look
On iOS you can display an .usdz 3D asset using a native AR UI

<img src="images/arquick.jpg" width="400"/>


---

## GamePad API
Allows to use a physical gamepad

---

## WebUSB API
Allows to use a physical gamepad

---

## Web Bluetooth API

---

## Web MIDI

---

## Web Locks API
Prevent display sleep and enable wake lock.

---

## Keyboard Lock
While in fullscreen, allows to receive keys that are normally handled by the system or the browser like Cmd/Alt-Tab, or Esc.

---

## Generic Sensor API
Allows to use several sensors like Accelerometer, Gyroscope, AmbientLightSensor, Magnetometer

---

## Credential Management API
Enables to store and retrieve password credentials, it elso enables tap to sign in and automatic sign back, password sharing on multiple device and many more.

<img src="images/sign.png" width="800"/>

---

## Clipboard API
Allow to read and write text and images into the OS clipboard buffer

---

## Presentation API
Gives ability to access external presentation-type displays and use them for presenting web content.

---

## Screen Orientation API
Read and lock screen orientation

---

## getUserMedia camera selection
When using camera/microphone, we can select the input source (example front or back camera). On the Pixel 4XL we can even access the infrared camera (used for face detection).

<img src="images/ir.png" width="300"/>

---

## Pointer Lock (Mouse Lock)
Gives access to raw mouse movement, locks the target of mouse events to a single element, eliminates limits of how far mouse movement can go in a single direction, and removes the cursor from view. Obvious use cases are for first person or real time strategy games.

---

## Theme Color
on Android you can customise tab color.

<img src="images/theme.png" width="300"/>

---

## Vibration API
Provides access to the vibration mechanism of the hosting device.

---

## Battery Status API
Allows access to see the battery level of the device's battery.

---

## Page Visibility API
Provides an API to ask whether the current tab is visible or not.

---

## Web Speech API
Enables web developers to incorporate speech recognition and speech synthesis.

---

## GPU chipset

---

## Memory

---

## CPU Cores
With `Navigator.hardwareConcurrency` you can get the n. of CPU cores available

---

## navigator.connection.downlinkMax, wimax, and onchange

---

# Stuff under Origin Trial

## Native File System
Allows access to the file system.

---

## SMS Receiver API
Allow the site to read received SMS, for example for OTP and phone number validation.

---

## Contacts API
Provide native UI to select contacts from your OS and retrieve informations.

---

## Badging API
Allows to set badge in OS in places like shelf or homescreen.

---