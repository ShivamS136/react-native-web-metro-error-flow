# react-native-web-metro-error-flow
This repo is just for sharing a test environment on [a bug](https://github.com/facebook/metro/issues/675) opened at facebook/metro repo and [a discussion](https://github.com/necolas/react-native-web/discussions/2052) opened in `react-native-web` repo.

**Steps to reproduce** are as below:
1. Download [this repo](https://github.com/ShivamS136/react-native-web-metro-error-flow) in your system.
2. `npm install`
3. `npm run web`

Now you'll see the error in the terminal.

**_Versions:_**

- metro-react-native-babel-preset: 0.66.0
- node: 16.3.0
- npm: 7.8.0
- OS: Windows 10 - 64 bit

---

## UPDATE:
Issue is found and resolved in [this commit](https://github.com/ShivamS136/react-native-web-metro-error-flow/commit/002aab5d72152901dac77d4ae88de84b24317cf7), more details are in [the discussion](https://github.com/necolas/react-native-web/discussions/2052) mentioned above.
