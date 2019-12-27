# Typescript_basic

![](https://img.shields.io/badge/Language-typescript-red) ![](https://img.shields.io/badge/Level-easy-yellow)

기본적인 Typescript를 정리한 Repository입니다.

------

## Download ([node.js](https://nodejs.org/en))

```js
$ node -v
v10.15.1
$ npm -v
6.4.1
```

#### Install node.js version manager "n"

```js
$ npm install -g n
$ n 10.0.0  # set version
$ n lts     # latest version
```

------

## What is npm?

- the world's largest Software Library (Registry)
- software Package Manager and Installer

#### install npm
```js
$ npm install <package>
```

#### update npm

```js
$ npm install -g npm@latest
```

------

## Typescript

#### For the latest stable version:

```js
$ npm install -g typescript
```

#### check the version:

```js
$ tsc -v
```

------

## Start

```js
$ mkdir <project-name>
$ npm init 
$ tsc --init
```
( created pakage.json, tsconfig.json )
```js
$ mkdir src
$ touch app.ts
```
( modify app.ts )
```js
$ tsc
$ node./dist/app.js
```
F5: ( tsc:build - tsconfig.json )

------
