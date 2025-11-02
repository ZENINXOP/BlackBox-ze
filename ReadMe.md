# 🚀 BlackBox Enhanced Edition

<p align="center">
  <img src="https://raw.githubusercontent.com/github/explore/main/topics/cube/cube.png" width="180" alt="BlackBox Logo"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Enhanced%20by-ZENINXOP-ff6b35.svg"/>
  <img src="https://img.shields.io/badge/Language-Java%20%7C%20Kotlin-blue.svg"/>
  <img src="https://img.shields.io/badge/Android-5.0%2B-green.svg"/>
  <img src="https://img.shields.io/badge/Supported-ARM64%20%7C%20ARMv7%20%7C%20x86-pink.svg"/>
  <img src="https://img.shields.io/badge/License-Apache%202.0-blue.svg"/>
</p>

---

> ⚠️ **Note:**  
> Free Version supports **Android 5.0 – 14** *(stable with minor bugs)*  
> Paid Version supports **Android 5.0 – 16** *(fully fixed, all features unlocked)*  

---

## 📖 Overview

**BlackBox Enhanced Edition** by **ZENINXOP** is a lightweight and optimized rebuild of the original BlackBox Virtual Engine.  
It allows you to **clone, run, and manage virtual apps** securely — **without root access**.

### ✨ Highlights
- Run multiple app instances  
- Full sandbox isolation  
- Built-in hidden Xposed support  
- Optimized for Android 8–14  
- UID, path, and crash fixes  
- Enhanced stability & performance  

---

## ⚙️ Technical Details

| Parameter | Value |
|------------|-------|
| **Min SDK** | 24 (Android 7.0) |
| **Target SDK** | 34 (Android 14) |
| **Compile SDK** | 35 |
| **NDK Version** | 29.0.13846066 |
| **JVM Target** | Java 17 |
| **Architectures** | ARM64-v8a / ARMv7a / x86 |
| **Edition** | Free (Android 5–14) / Paid (Android 5–16) |

---

## 🛠️ Fixes by ZENINXOP

- ✅ Fixed APK path & I/O errors  
- ✅ Solved UID mismatch crashes (Android 14 / MIUI)  
- ✅ Eliminated freezing & context issues  
- ✅ Improved memory management  
- ✅ Enhanced sandbox & UID handling  
- ✅ Added async operations & caching  

---

## ⚡ Quick Example

### Initialize
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

### Install & Launch
```java
File apk = new File("/sdcard/Download/app.apk");
BlackBoxCore.get().installPackageAsUser(apk, 0);
Intent i = BlackBoxCore.get().launchApk("com.example.app", 0);
startActivity(i);
```

---

## 💬 Paid Edition & Contact

> Want the **Paid Version (Android 5–16)** with all bugs fixed and full source?

📱 **Contact ZENINXOP:**  
- **Telegram:** [@ZENINXOP](https://t.me/ZENINXOP)  
- **YouTube:** [@ZENINXYT](https://youtube.com/@ZENIN_XYT)  
- **Binance ID (Support Dev):** `1025747286`

💼 **Paid Edition Includes:**
- All Android versions (5–16) supported  
- Full enhanced source code  
- Premium performance fixes  
- Direct developer support  
- Lifetime updates  

---

## 🧠 Credits

- **Enhanced Edition Developer:** [ZENINXOP](https://t.me/ZENINXOP)
- Based on:
  - [VirtualApp](https://github.com/asLody/VirtualApp)
  - [BlackReflection](https://github.com/CodingGay/BlackReflection)
  - [FreeReflection](https://github.com/tiann/FreeReflection)
  - [Dobby](https://github.com/jmpews/Dobby)

---

## ⚖️ License

```
Copyright 2024 ZENIN

Licensed under the Apache License, Version 2.0
http://www.apache.org/licenses/LICENSE-2.0
```
