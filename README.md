# Flycast

<img src="shell/linux/flycast.png" alt="flycast logo" width="150"/>

**Flycast** is a multi-platform Sega Dreamcast, Naomi, Naomi 2, and Atomiswave emulator derived from [**reicast**](https://github.com/skmp/reicast-emulator).

Information about configuration and supported features can be found on [**TheArcadeStriker's flycast wiki**](https://github.com/TheArcadeStriker/flycast-wiki/wiki).

### iOS

Clone the repository recursively:
```
git clone --recursive https://github.com/chachillie/Flycast-iOS.git
cd Flycast-iOS
```

Create the iOS build directory:
```
mkdir -p build-ios
cd build-ios
```

Generate Xcode project:
```
cmake .. -G Xcode -DCMAKE_SYSTEM_NAME=iOS
```

Open the generated Xcode project and build
