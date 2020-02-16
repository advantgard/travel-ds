# @travel-ds/babel-preset

Automatically load the css for the @travel-ds design system.

## Installation

```sh
npm i --save-dev @travel-ds/babel-preset
# or
yarn add -D @travel-ds/babel-preset
```

## Usage

.babelrc:

```json
{
  "presets": ["@travel-ds/babel-preset"]
}
```

## Example

Input:

```js
import Card from '@travel-ds/card';
```

Output:

```js
import Card from '@travel-ds/card';
import '@travel-ds/card/dist/main.css';
```
