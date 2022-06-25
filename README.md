# reactMobileTemplate
a tempate to create a react native "mobile" (react-native node pacakge module) thats contains a "shared" components used by a react native web app as well


The "shared" directory currently exist in this repo/project. This will be an an npm repo soon. the reactWebTemplate project makes a symlink to this shared code


tutorial on this concept of sharing code between web and mobile react apps
https://www.youtube.com/watch?v=2wOvhDtqsW8 Web and mobile apps using React Native Web with Robin Heinze


##Setup
make sure to install android studio
Follow these steps for your OS
https://reactnative.dev/docs/environment-setup

Make sure you have a ios/android emulator running, or a device connected via usb (adb devices) 

Then run 
npm install
yarn start  (to start the metro server)
then in another terminal .. run 
yarn android (or ios)

