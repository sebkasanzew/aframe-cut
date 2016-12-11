## aframe-cut-component

A Cut component for [A-Frame](https://aframe.io).

### API

| Property | Description | Default Value |
| -------- | ----------- | ------------- |
|          |             |               |

### Installation

#### Browser

Install and use by directly including the [browser files](dist):

```html
<head>
  <title>My A-Frame Scene</title>
  <script src="https://aframe.io/releases/0.3.2/aframe.min.js"></script>
  <script src="https://rawgit.com/Sebkasanzew/aframe-cut/master/dist/aframe-cut.min.js"></script>
</head>

<body>
  <a-scene>
    <a-entity cut="exampleProp: exampleVal"></a-entity>
  </a-scene>
</body>
```

#### npm

Install via npm:

```bash
npm install aframe-cut
```

Then register and use.

```js
require('aframe');
require('aframe-cut');
```
