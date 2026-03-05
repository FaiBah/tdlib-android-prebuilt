# TDLib Android Prebuilt

Prebuilt [TDLib](https://github.com/tdlib/td) libraries for Android, automatically compiled using GitHub Actions.

## Build

Go to **Actions** → **Build TDLib for Android** → **Run workflow**

## Usage

Copy files into your Android project:

```
app/src/main/
├── jniLibs/
│   ├── arm64-v8a/libtdjni.so
│   ├── armeabi-v7a/libtdjni.so
│   ├── x86/libtdjni.so
│   └── x86_64/libtdjni.so
└── java/org/drinkless/tdlib/
    ├── Client.java
    └── TdApi.java
```
