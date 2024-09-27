<p align="center">
<a href="https://www.npmjs.com/package/use-state-url" target="_blank" rel="noopener noreferrer">
<img src="https://api.iconify.design/carbon:url.svg?color=%23ffed7a" alt="logo" width='100'/></a>
</p>

<p align="center">
  A hook that stores the state into url query parameters. ✨
</p>

<p align="center">
  <a href="https://www.npmjs.com/package/use-state-url" target="_blank" rel="noopener noreferrer"><img src="https://badge.fury.io/js/use-state-url.svg" alt="NPM Version" /></a>
  <a href="https://www.npmjs.com/package/use-state-url" target="_blank" rel="noopener noreferrer"><img src="https://img.shields.io/npm/dt/use-state-url.svg?logo=npm" alt="NPM Downloads" /></a>
  <a href="https://bundlephobia.com/result?p=use-state-url" target="_blank" rel="noopener noreferrer"><img src="https://img.shields.io/bundlephobia/minzip/use-state-url" alt="Minizip" /></a>
  <a href="https://github.com/hunghg255/use-state-url/graphs/contributors" target="_blank" rel="noopener noreferrer"><img src="https://img.shields.io/badge/all_contributors-1-orange.svg" alt="Contributors" /></a>
  <a href="https://github.com/hunghg255/use-state-url/blob/main/LICENSE" target="_blank" rel="noopener noreferrer"><img src="https://badgen.net/github/license/hunghg255/use-state-url" alt="License" /></a>
</p>

## Installing

Inside your React project directory, run the following:

```bash
yarn add use-state-url -S
```

Or with npm:

```bash
npm install use-state-url -S
```

Or with pnpm

```bash
pnpm add use-state-url
```

Or with Bun

```bash
bun add use-state-url
```

## Example

```javascript
import useStateUrl from 'use-state-url';

const [state, setState] = useStateUrl({ demoCount: '1' }, options);
```

## useStateUrl Options

```ts
interface Options {
    navigateMode?: 'push' | 'replace';
    parseOptions?: ParseOptions;
    stringifyOptions?: StringifyOptions;
}
```
