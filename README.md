# react-native-geofence

## Getting started

`$ npm install react-native-geofence --save`

### Mostly automatic installation

`$ react-native link react-native-geofence`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-geofence` and add `Geofence.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libGeofence.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainApplication.java`
  - Add `import com.reactlibrary.GeofencePackage;` to the imports at the top of the file
  - Add `new GeofencePackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-geofence'
  	project(':react-native-geofence').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-geofence/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-geofence')
  	```


## Usage
```javascript
import Geofence from 'react-native-geofence';

// TODO: What to do with the module?
Geofence;
```
