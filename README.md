# react-native-mhttpcache

[![npm version](https://badge.fury.io/js/react-native-mhttpcache.svg)](https://badge.fury.io/js/react-native-mhttpcache)

React Native http cache control for both fetch/XMLHttpRequest and ImageView

本项目基于[react-native-http-cache](https://github.com/reactnativecn/react-native-http-cache)调整开发，感谢作者的贡献

- [x] iOS
- [x] Android

## 安装

```sh
npm install react-native-mhttpcache --save
```

## 使用

```js
import * as CacheManager from 'react-native-mhttpcache';

// invoke API directly when in need
CacheManager.clear();

```

## API 说明

### clear()

【Promise】清除所有缓存

### getSize()

【Promise】获取所有缓存大小（bytes）

### clearHttpCache()

【Promise】清除 fetch/ajax 缓存

### getHttpCacheSize()

【Promise】获取 fetch/ajax 缓存大小（bytes）

### clearImageCache()

【Promise】清除 ImageView 缓存

### getImageCacheSize()

【Promise】获取 ImageView 缓存大小（bytes）
