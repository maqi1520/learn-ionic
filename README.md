## Install Ionic
First, install Node.js 4 (Node 5 does not work at the moment!). Then, install the latest Cordova and Ionic command-line tools. Follow the Android and iOS platform guides to install required platform dependencies.

```
$ npm install -g cordova ionic
```

##Start a project

Create an Ionic project using one of our ready-made app templates, or a blank one to start fresh.

```
$ ionic start myApp tabs
```
other templates

```
$ ionic start myApp blank
```
```
$ ionic start myApp sidemenu
```


##Run it

Use the Ionic tool to build, test, and run your apps (or use Cordova directly). Make sure to substitute ios with android to build for Android.

Then, try Ionic View to share your apps with testers and clients, or to easily test on new devices.

```
$ cd myApp
$ ionic platform add ios
$ ionic build ios
$ ionic emulate ios
```