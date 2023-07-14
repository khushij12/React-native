# React-native
Using react native we can use single codepbase for android, ios , and web.

Commands:

```npm install expo```

```npx create-expo-app AppName```

```npm start```

Check Ruby version from react native environemnet set up doc

Use Xcode or Android studio for IDE

Setup can be created using:
1. Setup with expo
2. Setup a custom app
3. Setup Android Studio

```npm install eslint --save-dev```
```npx eslint --init```
```npm install @react-native-community/eslint-config --save-dev```

You can add rules for eslint in .eslintrc.js. Rules website url: "https://eslint.org/docs/latest/rules/"

```npm install --save-dev --save-exact prettier```

You can add rules for eslint in .prettierrc.js. Rules website url: https://prettier.io/docs/en/configuration.html

**To add ".code command in shell commands to open vs code:**
In command palette -> Install code command

To add navigation screens:
```npm install @react-navigation/native```
```npx expo install react-native-screens react-native-safe-area-context```
```npm install @react-navigation/native-stack```

Packages to use:
- https://www.nativewind.dev/

Note:
- The --save-dev option allows you to save packages under the devDependencies object in your package.json file. Any packages listed under the devDependencies will not be installed when you are in the production environment.
- 
<hr>

**useNavigation**
- useNavigation is a hook which gives access to navigation object.

**useLayoutEffect**
- useLayoutEffect is a version of useEffect that fires before the browser repaints the screen.

**SafeAreaView**
- The purpose of SafeAreaView is to render content within the safe area boundaries of a device. It is currently only applicable to iOS devices with iOS version 11 or later.

**Install react natice heroicons**
```npm i react-native-heroicons react-native-svg```


Working on this UI: [Link](https://www.figma.com/file/kUPJvUtB8ch6f9frDKn97I/Eatme---Food-Delivery-UI-Kit?type=design&node-id=58-31&mode=design&t=4WFfx3KdGidncVrv-0)

## Image
A React component for displaying different types of images, including network images, static resources, temporary local images, and images from local disk, such as the camera roll.

```html
      <Image
        style={styles.tinyLogo}
        source={require('@expo/snack-static/react-native-logo.png')}
      />
      <Image
        style={styles.tinyLogo}
        source={{
          uri: 'https://reactnative.dev/img/tiny_logo.png',
        }}
      />
      <Image
        style={styles.logo}
        source={{
          uri: 'data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADMAAAAzCAYAAAA6oTAqAAAAEXRFWHRTb2Z0d2FyZQBwbmdjcnVzaEB1SfMAAABQSURBVGje7dSxCQBACARB+2/ab8BEeQNhFi6WSYzYLYudDQYGBgYGBgYGBgYGBgYGBgZmcvDqYGBgmhivGQYGBgYGBgYGBgYGBgYGBgbmQw+P/eMrC5UTVAAAAABJRU5ErkJggg==',
        }}
      />
```

blurRadius: To blur the the image
