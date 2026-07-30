# 🚀 ZCore — BlackBox Enhanced Edition

<p align="center">
  <img src="https://raw.githubusercontent.com/github/explore/main/topics/cube/cube.png" width="180" alt="ZCore BlackBox Logo"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Project-ZCore-8a2be2.svg"/>
  <img src="https://img.shields.io/badge/Enhanced%20by-ZENINXOP-ff6b35.svg"/>
  <img src="https://img.shields.io/badge/GMS-Compatible-success.svg"/>
  <img src="https://img.shields.io/badge/Language-Java%20%7C%20Kotlin-blue.svg"/>
  <img src="https://img.shields.io/badge/Android-5.0--17-green.svg"/>
  <img src="https://img.shields.io/badge/Supported-ARM64%20%7C%20ARMv7%20%7C%20x86-pink.svg"/>
  <img src="https://img.shields.io/badge/License-Apache%202.0-blue.svg"/>
</p>

---

> [!IMPORTANT]
> **ZCore** is an enhanced Android virtual application engine based on the upstream **BlackBox Virtual Engine**.
>
> It includes modern Android compatibility fixes, improved sandbox handling, Google Mobile Services compatibility, performance improvements, and extended support for Android versions up to **Android 17**.

> [!NOTE]
> **Free Edition:** Supports Android 5.0–14 with some known limitations.
> **Paid Edition:** Supports Android 5.0–17 with extended fixes, GMS compatibility, and premium features.

---

## 📖 Overview

**ZCore — BlackBox Enhanced Edition**, developed by **ZENINXOP**, is a lightweight and optimized Android virtualization framework built on top of the BlackBox Virtual Engine.

It allows applications to be installed, cloned, launched, and managed inside an isolated virtual environment without requiring root access.

ZCore extends the original BlackBox architecture with additional improvements for modern Android versions, custom Android ROMs, virtual processes, package management, account services, storage handling, Google Play Services, and Google account authentication.

---

## ✨ Main Features

* Run multiple instances of Android applications
* Clone applications without modifying their original APK
* Install and manage applications inside a virtual environment
* Full virtual application sandbox isolation
* No root access required
* Built-in hidden Xposed module support
* Google Mobile Services compatibility
* Google account login support
* Google Play Services support
* Google Play Store compatibility
* Virtual package, activity, account, job, and storage services
* Android 5.0–17 compatibility
* Improved support for Android 14, 15, 16, and 17
* Application UID and virtual path fixes
* Improved application lifecycle management
* Improved process and service handling
* Improved crash prevention and memory management
* Support for ARM64, ARMv7, and x86 architectures

---

## 🔥 ZCore Enhancements

ZCore adds an extended compatibility, performance, and stability layer on top of the original BlackBox engine.

### Core Improvements

* Improved virtual process initialization
* Improved virtual application lifecycle handling
* Improved application context creation
* Improved application and user-data isolation
* Fixed incorrect APK installation paths
* Fixed native library path issues
* Fixed application file I/O errors
* Improved virtual UID allocation
* Improved UID mapping and sandbox handling
* Improved virtual package installation
* Improved package removal and cleanup
* Improved virtual user management
* Improved application-data deletion
* Improved external storage redirection
* Improved OBB path handling
* Improved Android service delegation
* Improved application startup performance
* Reduced application freezes and startup failures
* Improved asynchronous operations
* Added internal caching
* Improved memory usage
* Improved compatibility with custom Android ROMs

---

## 📱 Android 17 Compatibility

ZCore includes extended compatibility changes for Android versions up to **Android 17**.

### Android 15–17 Improvements

* Updated package-management compatibility
* Updated application process handling
* Improved storage-access compatibility
* Improved scoped-storage redirection
* Improved virtual application-data paths
* Improved native library loading
* Improved service binding
* Improved activity-launch handling
* Improved foreground-service compatibility
* Improved notification handling
* Improved background-job handling
* Improved application permission handling
* Improved account-service compatibility
* Improved Android framework method compatibility
* Improved compatibility with newer Android security restrictions
* Improved support for modern custom ROMs

> [!WARNING]
> Android 17 compatibility can depend on the final Android framework changes, device ROM, application security, processor architecture, and manufacturer-specific restrictions.
>
> Some applications may require additional application-specific compatibility fixes.

---

## 🧩 Google Mobile Services Compatibility

ZCore includes extended compatibility for applications that depend on **Google Mobile Services**, commonly known as **GMS**.

### Supported GMS Components

* Google Play Services
* Google Services Framework
* Google Play Store
* Google Account Manager
* Google account login
* Google authentication services
* Google OAuth login flows
* Applications using Google Play Services APIs
* Applications requiring Google account access
* Applications using Google background services
* Applications depending on Google service bindings
* Applications using Firebase-related Google services

### GMS Compatibility Improvements

* Improved Google account-service binding
* Improved authentication-manager delegation
* Improved Google Play Services process handling
* Improved Google Services Framework compatibility
* Improved virtual account storage
* Improved Google account persistence
* Improved Google login flow
* Improved package visibility between Google components
* Improved service-connection handling
* Improved Google background services
* Improved GMS job scheduling
* Improved GMS application startup
* Improved Play Store launch compatibility
* Improved account synchronization handling
* Fixed several Google authentication crashes
* Fixed several disconnected service issues
* Fixed several GMS process startup failures

> [!WARNING]
> GMS compatibility may vary depending on:
>
> * Android version
> * Google Play Services version
> * Device manufacturer
> * Device ROM
> * Application security checks
> * Play Integrity requirements
> * Hardware-backed attestation
> * Google account security policies
>
> Applications using hardware-backed verification, advanced Play Integrity checks, DRM, anti-cheat systems, or anti-virtualization protections may not work correctly inside a virtual environment.

---

## 🏗️ ZCore Architecture

ZCore virtualizes and manages important Android framework components.

| Virtual Service             | Purpose                                                                     |
| --------------------------- | --------------------------------------------------------------------------- |
| **Activity Manager**        | Controls virtual activities, processes, tasks, and application lifecycle    |
| **Package Manager**         | Installs, removes, and manages virtual applications                         |
| **Account Manager**         | Manages virtual application accounts and Google accounts                    |
| **Job Manager**             | Handles scheduled jobs and background tasks                                 |
| **Storage Manager**         | Redirects application files into isolated virtual storage                   |
| **User Manager**            | Manages multiple virtual users and cloned application instances             |
| **Notification Manager**    | Handles notifications created by virtual applications                       |
| **Location Manager**        | Provides virtual location-service compatibility                             |
| **Xposed Manager**          | Loads and manages supported hidden Xposed modules                           |
| **Process Manager**         | Creates and manages virtual application processes                           |
| **Permission Manager**      | Handles permissions inside the virtual environment                          |
| **GMS Compatibility Layer** | Handles Google services, authentication, accounts, and related dependencies |

---

## ⚙️ Technical Details

| Parameter                     | Value                             |
| ----------------------------- | --------------------------------- |
| **Project Name**              | ZCore — BlackBox Enhanced Edition |
| **Base Engine**               | BlackBox Virtual Engine           |
| **Developer**                 | ZENINXOP                          |
| **Minimum Supported Android** | Android 5.0                       |
| **Maximum Supported Android** | Android 17                        |
| **Minimum SDK**               | Project-dependent                 |
| **Target SDK**                | Android 14                        |
| **Compile SDK**               | Android SDK 35                    |
| **NDK Version**               | 29.0.13846066                     |
| **JVM Target**                | Java 17                           |
| **Languages**                 | Java and Kotlin                   |
| **Architectures**             | ARM64-v8a / ARMv7a / x86          |
| **Root Required**             | No                                |
| **GMS Compatibility**         | Available                         |
| **Google Account Login**      | Supported                         |
| **Free Edition**              | Android 5.0–14                    |
| **Paid Edition**              | Android 5.0–17                    |

---

## 🛠️ Fixes by ZENINXOP

* ✅ Fixed APK path and file I/O errors
* ✅ Fixed virtual application-data paths
* ✅ Fixed native library loading paths
* ✅ Fixed UID mismatch crashes
* ✅ Fixed application context errors
* ✅ Fixed virtual process startup issues
* ✅ Fixed application freezing issues
* ✅ Fixed package installation failures
* ✅ Fixed package-removal cleanup
* ✅ Fixed virtual user-data removal
* ✅ Fixed external storage redirection
* ✅ Fixed OBB path handling
* ✅ Fixed service-connection issues
* ✅ Fixed several Google account login issues
* ✅ Fixed several Google Play Services startup issues
* ✅ Fixed GMS background-process handling
* ✅ Improved Android 14 compatibility
* ✅ Improved Android 15 compatibility
* ✅ Improved Android 16 compatibility
* ✅ Improved Android 17 compatibility
* ✅ Improved MIUI compatibility
* ✅ Improved HyperOS compatibility
* ✅ Improved ColorOS compatibility
* ✅ Improved OxygenOS compatibility
* ✅ Improved One UI compatibility
* ✅ Improved virtual memory management
* ✅ Improved sandbox and UID handling
* ✅ Improved application lifecycle management
* ✅ Improved package-management compatibility
* ✅ Improved account-service handling
* ✅ Improved background jobs
* ✅ Improved notification handling
* ✅ Improved application startup speed
* ✅ Added asynchronous operations
* ✅ Added internal caching
* ✅ Reduced unnecessary process restarts
* ✅ Improved overall stability and performance

---

## ⚡ Quick Example

### Initialize ZCore

```java
@Override
protected void attachBaseContext(Context base) {
    super.attachBaseContext(base);

    BlackBoxCore.get().doAttachBaseContext(base);
}

@Override
public void onCreate() {
    super.onCreate();

    BlackBoxCore.get().doCreate();
}
```

---

### Install an Application

```java
File apkFile = new File("/sdcard/Download/application.apk");

BlackBoxCore.get().installPackageAsUser(
        apkFile,
        0
);
```

---

### Launch an Application

```java
String packageName = "com.example.application";
int userId = 0;

Intent launchIntent = BlackBoxCore.get().launchApk(
        packageName,
        userId
);

if (launchIntent != null) {
    startActivity(launchIntent);
}
```

---

### Launch an Application in a New Task

```java
String packageName = "com.example.application";
int userId = 0;

Intent launchIntent = BlackBoxCore.get().launchApk(
        packageName,
        userId
);

if (launchIntent != null) {
    launchIntent.addFlags(Intent.FLAG_ACTIVITY_NEW_TASK);
    startActivity(launchIntent);
}
```

---

### Install for Another Virtual User

```java
File apkFile = new File("/sdcard/Download/application.apk");
int userId = 1;

BlackBoxCore.get().installPackageAsUser(
        apkFile,
        userId
);
```

---

## 📊 Android Version Support

| Android Version |                       Free Edition |      Paid Edition |
| --------------- | ---------------------------------: | ----------------: |
| Android 5.0–7.1 |                        ✅ Supported |       ✅ Supported |
| Android 8–10    |                        ✅ Supported |       ✅ Supported |
| Android 11–13   |                        ✅ Supported |       ✅ Supported |
| Android 14      | ✅ Supported with minor limitations | ✅ Fully optimized |
| Android 15      |         ⚠️ Limited or experimental |       ✅ Supported |
| Android 16      |                     ❌ Not included |       ✅ Supported |
| Android 17      |                     ❌ Not included |       ✅ Supported |

> [!NOTE]
> Actual application compatibility may vary depending on the application, Android build, device manufacturer, processor architecture, security checks, Google Play Services version, and custom ROM.

---

## 💼 Free Edition

The Free Edition provides the core BlackBox and ZCore virtualization functionality.

### Free Edition Includes

* Android 5.0–14 support
* Basic application cloning
* Virtual application installation
* Multiple virtual users
* Basic sandbox isolation
* Virtual package management
* Virtual storage management
* Basic application lifecycle handling
* ARM64, ARMv7, and x86 support
* Community-level updates

### Free Edition Limitations

* Limited Android 15 compatibility
* Android 16 not included
* Android 17 not included
* Some GMS features may have limitations
* Some custom-ROM fixes may not be included
* Application-specific fixes may not be included
* Premium source-code changes are not included

---

## 💎 Paid Edition

The Paid Edition includes the complete enhanced ZCore source code and extended compatibility improvements for Android 5.0 through Android 17.

### Paid Edition Includes

* Android 5.0–17 compatibility
* Complete enhanced ZCore source code
* Android 15 compatibility fixes
* Android 16 compatibility fixes
* Android 17 compatibility fixes
* Extended Google Mobile Services compatibility
* Improved Google account login
* Improved Google Play Services handling
* Improved Google Services Framework handling
* Improved Play Store compatibility
* Improved process and service handling
* Improved storage compatibility
* Improved package-management compatibility
* Improved virtual user management
* Improved account-management compatibility
* Improved custom-ROM compatibility
* Premium performance optimizations
* Application-specific compatibility fixes
* Direct developer support
* Lifetime updates

---

## 💬 Paid Edition and Contact

For Paid Edition details, complete source-code access, compatibility support, or custom development, contact **ZENINXOP**.

* **Telegram:** [@ZENINXOP](https://t.me/ZENINXOP)
* **YouTube:** [@ZENINXYT](https://youtube.com/@ZENIN_XYT)
* **Binance ID:** `1243066564`

---

## ⚠️ Compatibility Notice

ZCore does not guarantee compatibility with every Android application.

Applications using the following technologies may require additional fixes or may not work inside a virtual environment:

* Google Play Integrity
* Hardware-backed attestation
* Strong Integrity verification
* Device Integrity verification
* DRM protection
* Anti-cheat systems
* Anti-tampering systems
* Root and virtualization detection
* Advanced anti-emulator checks
* Hardware security modules
* Manufacturer-specific security frameworks
* Biometric hardware verification
* Banking application security checks

---

## ⚠️ Disclaimer

ZCore is intended for legitimate purposes, including:

* Android application development
* Application compatibility testing
* Sandbox testing
* Multi-account usage
* Privacy testing
* Application debugging
* Virtualization research
* Google service compatibility research
* Security research on applications you own or are authorized to test

Users and developers are responsible for ensuring their usage complies with:

* Applicable laws
* Application terms of service
* Google service policies
* Software licenses
* Device-manufacturer policies
* Third-party service requirements

ZCore is an independent enhanced project built on the BlackBox Virtual Engine.

It is not officially endorsed by Google, Android, device manufacturers, application developers, or the original BlackBox contributors unless explicitly stated by those parties.

---

## 🧠 Credits

### ZCore Development

* **Enhanced Edition Developer:** [ZENINXOP](https://t.me/ZENINXOP)

### Based On and Inspired By

* BlackBox Virtual Engine
* [VirtualApp](https://github.com/asLody/VirtualApp)
* [BlackReflection](https://github.com/CodingGay/BlackReflection)
* [FreeReflection](https://github.com/tiann/FreeReflection)
* [Dobby](https://github.com/jmpews/Dobby)

Special thanks to all upstream developers and open-source contributors whose work helped make this project possible.

---

## ⚖️ License

```text
Copyright 2024–2026 ZENIN

Licensed under the Apache License, Version 2.0.

You may obtain a copy of the License at:

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.

See the License for the specific language governing permissions and
limitations under the License.
```
