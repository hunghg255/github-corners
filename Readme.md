
[![npm version](https://badge.fury.io/js/gh-corners.svg)](https://badge.fury.io/js/gh-corners) [![npm](https://img.shields.io/npm/dt/gh-corners.svg?logo=npm)](https://www.npmjs.com/package/gh-corners) [![npm](https://img.shields.io/bundlephobia/minzip/gh-corners)](https://www.npmjs.com/package/gh-corners)
[![All Contributors](https://img.shields.io/badge/all_contributors-1-orange.svg)](#contributors-)

[Live Demo](https://github-corners.vercel.app/)

## Installation

[![NPM](https://nodei.co/npm/gh-corners.png?compact=true)](https://nodei.co/npm/gh-corners/)


# Package

```js
import 'gh-corners';
```

# unpkg.com CDN:

```js
<script type="module" src="https://unpkg.com/gh-corners@latest"></script>
```

# HTML
```
<github-corners target="__blank" position="fixed" href="https://github.com/hunghg255"></github-corners>
```

# Reactjs

[react-gh-corners](https://www.npmjs.com/package/react-gh-corners)

```
npm i react-gh-corners@latest
```

# Use

```tsx
import { GithubCorners } from 'react-gh-corners';

// Nextjs only CSR
const GithubCorners = dynamic(() => import('react-gh-corners').then((m) => m.GithubCorners), {
  ssr: false,
});


const App = () => {
  return (
    <GithubCorners position='right' href='/' />
  );
};
```
