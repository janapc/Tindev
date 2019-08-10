# Tindev
prototype based in Tinder for developers

##Notes
There are three folders:
 - **backend** = Api
 - **frontend** = application for browser
 - **mobile** = application for mobile

## Getting Started

to run the application on your computer you must have installed some packages

### Prerequisites

  - React-native
    ```
      npm install -g react-native-cli
    ```

  - Nodejs
    ```
      https://nodejs.org/en/download/
    ```

  - Android Studio
    ```
      https://developer.android.com/studio
    ```

  - Xcode
    ```
      https://developer.apple.com/xcode/
    ```

### Installing


Here is the step by step that should be followed to run your application once you have installed the prerequisites:

 install the dependencies(for each folder):
```
yarn
```
enter the backend folder and run the command below to start the API:
```
yarn dev
```
enter the backend folder and run the command below to start the application browser:
```
yarn start
```
in the folder mobile/ios and:
```
 pod install
```
 run mobile:
```
yarn react-native run-android/run-ios
```
### Demo

![tindev Demo](screen/test.gif)


## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
