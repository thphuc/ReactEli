# ReactEli
Learn React Native with Android Team at Elinext

- React Native Offical Docs: https://facebook.github.io/react-native/docs/getting-started.html

If you get error "unable to load script from assets index.android.bundle", follow below steps to solve:
1. (In project directory) mkdir android/app/src/main/assets
2. react-native bundle --platform android --dev false --entry-file index.js --bundle-output android/app/src/main/assets/index.android.bundle --assets-dest android/app/src/main/res
3. react-native run-android
