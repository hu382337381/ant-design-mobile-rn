English | [简体中文](./README.zh-CN.md)

<p align="center">
  <a href="http://rn.mobile.ant.design">
    <img width="320" src="https://zos.alipayobjects.com/rmsportal/wIjMDnsrDoPPcIV.png">
  </a>
</p>

# Ant Design Mobile RN

[![](https://img.shields.io/travis/ant-design/ant-design-mobile-rn.svg?style=flat-square)](https://travis-ci.org/ant-design/ant-design-mobile-rn)
[![Codecov](https://img.shields.io/codecov/c/github/ant-design/ant-design-mobile-rn.svg?style=flat-square)](https://codecov.io/gh/ant-design/ant-design-mobile-rn)
[![npm package](https://img.shields.io/npm/v/@ant-design/react-native.svg?style=flat-square)](https://www.npmjs.org/package/@ant-design/react-native)
[![NPM downloads](http://img.shields.io/npm/dm/@ant-design/react-native.svg?style=flat-square)](https://npmjs.org/package/@ant-design/react-native)
[![Dependency Status](https://david-dm.org/ant-design/ant-design-mobile-rn.svg?style=flat-square)](https://david-dm.org/ant-design/ant-design-mobile-rn)
[![Percentage of issues still open](http://isitmaintained.com/badge/open/ant-design/ant-design-mobile-rn.svg)](http://isitmaintained.com/project/ant-design/ant-design-mobile-rn 'Percentage of issues still open')
[![Join the chat at https://gitter.im/ant-design/ant-design](https://img.shields.io/gitter/room/ant-design/ant-design.svg?style=flat-square)](https://gitter.im/ant-design/ant-design?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

A configurable Mobile UI specification and React-based implementation.

## Features

- Follow Ant Design Mobile UI specification.
- Configurable UI style for different products.
- Support web and native usages based on React Native.
- Develop in TypeScript.

## Demo

```bash
# clone
git clone git@github.com:ant-design/ant-design-mobile-rn.git

# go to ant rn folder
cd ant-design-mobile-rn

# install dependencies
yarn

# start ios simulator or android
# cd rn-kitchen-sink/ios && pod install
yarn ios # or yarn android

```

## Install & Usage

```bash
$ npm install @ant-design/react-native --save
```

or

```bash
yarn add @ant-design/react-native
```

### Installing peer dependencies

```bash
npm install @react-native-community/cameraroll @react-native-picker/picker @react-native-community/segmented-control @react-native-community/slider react-native-pager-view
```

or

```bash
yarn add @react-native-community/cameraroll @react-native-picker/picker @react-native-community/segmented-control @react-native-community/slider react-native-pager-view
```

> You need go to ios folder and run `pod install` (auto linking)，Android will handle it by itself.

### Link icon fonts

```bash
npx react-native link
```

[introduce](docs/react/introduce.en-US.md#安装)

## Links

- [Home Page](http://rn.mobile.ant.design)
- [Developer Instruction](development.en-US.md)
- [React components](http://github.com/react-component/)
- [Demos](https://github.com/ant-design/antd-mobile-samples)

## Contributing

We welcome all contributions, please read our [CONTRIBUTING.md](https://github.com/ant-design/ant-design-mobile-rn/blob/master/.github/CONTRIBUTING.md) first. You can submit any ideas as [pull requests](https://github.com/ant-design/ant-design-mobile-rn/pulls) or as a [GitHub issue](https://github.com/ant-design/ant-design-mobile-rn/issues). If you'd like to improve code, check out the [Development Instruction](https://github.com/ant-design/ant-design-mobile-rn/blob/master/development.en-US.md) and have a good time! :)
