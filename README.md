
# react-native-card-view

## Getting started

`$ npm install react-native-card-view --save`

### Mostly automatic installation

`$ react-native link react-native-card-view`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-card-view` and add `RNCardView.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libRNCardView.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import com.quenice.cardView.RNCardViewPackage;` to the imports at the top of the file
  - Add `new RNCardViewPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-card-view'
  	project(':react-native-card-view').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-card-view/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-card-view')
  	```


## Usage
```javascript
import RNCardView from 'react-native-card-view';

// TODO: What to do with the module?
RNCardView;
```
  # RNCardView
