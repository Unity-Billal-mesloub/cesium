# @cesium/widgets

[![Build Status](https://github.com/Unity-Billal-mesloub/cesium/actions/workflows/dev.yml/badge.svg)](https://github.com/Unity-Billal-mesloub/cesium/actions/workflows/dev.yml)
[![npm](https://img.shields.io/npm/v/@cesium/widgets)](https://www.npmjs.com/package/@cesium/widgets)
[![Docs](https://img.shields.io/badge/docs-online-orange.svg)](https://cesium.com/learn/)

![Cesium](https://github.com/Unity-Billal-mesloub/cesium/wiki/logos/Cesium_Logo_Color.jpg)

[CesiumJS](../../README.md) is a JavaScript library for creating 3D globes and 2D maps in a web browser without a plugin. It uses WebGL for hardware-accelerated graphics, and is cross-platform, cross-browser, and tuned for dynamic-data visualization.

`@cesium/widgets` is a widgets library for use with CesiumJS—including the `CesiumViewer` widget plus widgets for common tasks such as animation, base layer selection and geocoding.

---

[**Examples**](https://sandcastle.cesium.com/) :earth_asia: [**Docs**](https://cesium.com/learn/cesiumjs-learn/) :earth_americas: [**Website**](https://cesium.com/cesiumjs) :earth_africa: [**Forum**](https://community.cesium.com/) :earth_asia: [**User Stories**](https://cesium.com/user-stories/)

---

## Install

`@cesium/widgets` is published as ES modules with full typing support.

Install with npm

```sh
npm install @cesium/widgets --save
```

Or, install with yarn

```sh
yarn add @cesium/widgets
```

## Usage

Import individual modules to benefit from tree shaking optimizations through most build tools:

```js
import { Viewer } from "@cesium/widgets";
import "@cesium/widgets/Source/widgets.css";

const viewer = new Viewer("cesiumContainer");
```

See our [Quickstart Guide](https://cesium.com/learn/cesiumjs-learn/cesiumjs-quickstart/) for more information on getting a CesiumJS app up and running.


