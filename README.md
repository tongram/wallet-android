Use this software at your own risk; consult the DISCLAIMER for more information.

The source code is published under MIT with OpenSSL and [TON Testnet Wallet Android](https://github.com/ton-blockchain/wallet-android) exception, the licenses is available [here](https://github.com/tongram/wallet-android/blob/master/LICENSE) and [here](https://github.com/tongram/wallet-android/blob/master/LICENSE.GPL-2.0).


## Test Gram Wallet (Android)

This is the source code and build instructions for a TON Testnet Wallet implementation for Android.

### How to build

1. Install Android Studio 3.5.1, Android 10.0 SDK and Android NDK 20.0.5594570 
2. Place your release.keystore file into the **app/config** folder.
3. Open gradle.properties and fill **RELEASE_KEY_PASSWORD**, **RELEASE_KEY_ALIAS** and **RELEASE_STORE_PASSWORD** with values to access your keystore.
4. Open the project in the Android Studio (note that it should be opened, NOT imported) and build.
