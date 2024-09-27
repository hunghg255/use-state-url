# useStateUrl

A hook that stores the state into url query parameters.

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
import useUrlState from 'use-state-url';

const [state, setState] = useUrlState({ demoCount: '1' });
```


