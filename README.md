
# react-native-smtp-mailer

## Getting started

`$ npm install react-native-smtp-mailer --save`

### Mostly automatic installation

`$ react-native link react-native-smtp-mailer`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-smtp-mailer` and add `RNSmtpMailer.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libRNSmtpMailer.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import com.reactlibrary.RNSmtpMailerPackage;` to the imports at the top of the file
  - Add `new RNSmtpMailerPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-smtp-mailer'
  	project(':react-native-smtp-mailer').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-smtp-mailer/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-smtp-mailer')
  	```


## Usage
```javascript
import RNSmtpMailer from 'react-native-smtp-mailer';

// TODO: What to do with the module?
RNSmtpMailer;
```
  