[![CircleCI branch](https://img.shields.io/circleci/project/github/duxianwei520/react/master.svg?style=flat-square)](https://circleci.com/gh/duxianwei520/react)
[![GitHub forks](https://img.shields.io/github/forks/duxianwei520/react.svg)](https://github.com/duxianwei520/react/network)
[![GitHub stars](https://img.shields.io/github/stars/duxianwei520/react.svg)](https://github.com/duxianwei520/react/stargazers)
[![GitHub issues](https://img.shields.io/github/issues/duxianwei520/react.svg)](https://github.com/duxianwei520/react/issues)
[![GitHub license](https://img.shields.io/github/license/duxianwei520/react.svg)](https://github.com/duxianwei520/react/blob/master/LICENSE)
[![Coverage Status](https://coveralls.io/repos/github/duxianwei520/react/badge.svg)](https://coveralls.io/github/duxianwei520/react)

## Project technology stack

node10.15.3 + react@16.12.0 + redux@3.7.2 + react-router@3.2.0 + webpack@4.41.2 + axios@0.19.0 + less@2.7.1 + antd@3.25.2

## Project run


```
git clone --depth 1 https://github.com/duxianwei520/react.git  

cd react

npm install

npm start

```

## screenshots


### login

<img src="https://github.com/duxianwei520/resource/blob/master/react/screenshots/login.gif" width="973" height="557"/>

### echart

<img src="https://github.com/duxianwei520/resource/blob/master/react/screenshots/echart.gif" width="973" height="557"/>


### set center

<img src="https://github.com/duxianwei520/resource/blob/master/react/screenshots/set.gif" width="973" height="557"/>


### webpack bundle analysis

<img src="https://github.com/duxianwei520/resource/blob/master/react/screenshots/analysis.gif" width="973" height="557"/>

### build dist folder

<img src="https://github.com/duxianwei520/resource/blob/master/react/screenshots/dist.gif" width="973" height="557"/>


Final build command
```
npm run build
npm run testing

```

The data format returned by the server is also standard json, as shown below

```
{
  data: {
    totalCount: 100,
    currentPage: 1,
    pageSize: 10,
    'list': [
    ],
  },
  msg: '',
  status: 1,
}

```
