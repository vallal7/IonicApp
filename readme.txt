This is an Hybrid app build in ionic over cordova (Phonegap). This will support various platforms like ios, android, windows...
Setup is very much similar to ionic

1. Install node.js
2. Install cordova - $ npm install -g cordova
3. Install ionic - $ npm install -g cordova ionic
3. Create your app - $ ionic start myApp tabs
4. Navigate into your app and add any platform:
  cd MyApp
  ionic platform add ios
5. Build your app and run in simulator or device:
  $ ionic build ios
  $ ionic emulate ios
  
  $ ionic run ios

