# react-native-true

## Getting started

`$ npm install react-native-true --save`

### Mostly automatic installation

`$ react-native link react-native-true`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-true` and add `CBTrue.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libCBTrue.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainApplication.java`
  - Add `import dev.identivnox.rncrisp.CBTruePackage;` to the imports at the top of the file
  - Add `new CBTruePackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-true'
  	project(':react-native-true').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-true/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-true')
  	```


## Usage
```javascript
import CBTrue from 'react-native-true';

// TODO: What to do with the module?
CBTrue;
```
