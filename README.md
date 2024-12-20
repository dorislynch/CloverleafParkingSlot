
# react-native-cloverleaf-parking-slot

## Getting started

`$ npm install react-native-cloverleaf-parking-slot --save`

### Mostly automatic installation

`$ react-native link react-native-cloverleaf-parking-slot`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-cloverleaf-parking-slot` and add `RNCloverleafParkingSlot.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libRNCloverleafParkingSlot.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import com.reactlibrary.RNCloverleafParkingSlotPackage;` to the imports at the top of the file
  - Add `new RNCloverleafParkingSlotPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-cloverleaf-parking-slot'
  	project(':react-native-cloverleaf-parking-slot').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-cloverleaf-parking-slot/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-cloverleaf-parking-slot')
  	```

#### Windows
[Read it! :D](https://github.com/ReactWindows/react-native)

1. In Visual Studio add the `RNCloverleafParkingSlot.sln` in `node_modules/react-native-cloverleaf-parking-slot/windows/RNCloverleafParkingSlot.sln` folder to their solution, reference from their app.
2. Open up your `MainPage.cs` app
  - Add `using Cloverleaf.Parking.Slot.RNCloverleafParkingSlot;` to the usings at the top of the file
  - Add `new RNCloverleafParkingSlotPackage()` to the `List<IReactPackage>` returned by the `Packages` method


## Usage
```javascript
import RNCloverleafParkingSlot from 'react-native-cloverleaf-parking-slot';

// TODO: What to do with the module?
RNCloverleafParkingSlot;
```
  