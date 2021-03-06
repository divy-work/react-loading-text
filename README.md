## react-loading-text

![](./assets/demo.gif)

A simple module to display all types of weird sentences while your application loads.

![React CI](https://github.com/divy-work/react-loading-text/workflows/React%20CI/badge.svg)

## Installation

```sh
$ npm i @divy-work/react-loading-text
```

## Usage

```js
import React from 'react';
import LoadingText from '@divy-work/react-loading-text';

class LoadingView extends React.Component {
	render() {
		return (
			<LoadingText />
		)
	}
}
```

You can also specify additional statements and the interval time.

```js
<LoadingText extras={["Another Loading Text", "One more!"]} interval={4000} />
```
