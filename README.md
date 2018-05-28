# React Power Picture

Render images in your React application that take advantage of progressive loading as well as responsive sizing.

## Installation

This module is distributed via [npm](https://www.npmjs.com/) which is bundled with [node](https://nodejs.org/) and
should be installed as one of your project's `dependencies`:

```
npm install --save react-power-picture
```

> This package also depends on `react` and `prop-types`. Please make sure you
> have those installed as well.

## Usage

```jsx
import React from 'react';
import { render } from 'react-dom';
import PowerPicture from 'react-power-picture';

render(<PowerPicture />, document.getElementById('root'));
```

## Examples

A live example of this in action can be found on the [project's GitHub page](https://tvthatsme.github.io/react-power-picture).

## Inspiration

This project has been heavily inspired by the work of Formidable Labs and their [react-progressive-image](https://github.com/FormidableLabs/react-progressive-image) library. It does many things exactly right but did not provide the responsive solution that I was originally looking for.

Another shoutout to the [react-simple-image](https://github.com/bitjourney/react-simple-image) library. This project has everything for responsive images loaded as a `srcset` but with much broader prop support and less render flexibiliy.

You might consider React Power Picture to be a marriage of the two. My goad for this library to provide both progressive and responsive power.

## License

MIT
