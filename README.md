# react-native-flipper-databases

> Flipper Databases plugin for React Native

This [React Native](https://reactnative.dev) plugin allows browsing popular React Native databases using [Flipper](https://fbflipper.com) built-in Databases plugin.

## Installation

```sh
yarn add -D react-native-flipper react-native-flipper-databases
```

## Usage

```js
// ...

/// ReactNativeFlipperDatabases - START

if (__DEV__) {
  // Import connectDatabases function
  const connectDatabases = require('react-native-flipper-databases').default;

  // Import required DBDrivers
  const WatermelonDBDriver = require('react-native-flipper-databases/drivers/watermelondb').default;

  connectDatabases([
    new WatermelonDBDriver(database), // Pass in database definition
  ]);
}

/// ReactNativeFlipperDatabases - END

// ...
```

## Contributing

See the [contributing guide](CONTRIBUTING.md) to learn how to contribute to the repository and the development workflow.

## License

MIT

---

Made with :sparkles: & :heart: by [Mattia Panzeri](https://github.com/panz3r) and [contributors](https://github.com/panz3r/react-native-flipper-databases/graphs/contributors)

If you found this project to be helpful, please consider buying me a coffee.

[![buy me a coffee](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://buymeacoff.ee/4f18nT0Nk)
