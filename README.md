# react-simpple-virtualized-select-box

## About

Inspired react-virtualized I create this select box. It is very fast for big data and very simple and small.

It has only two dependencies, there are react and react-dom.

You can customize it as you need.

## Exapmle

![video example](https://github.com/or4/react-simpple-virtualized-select-box/blob/master/video.gif)

## Install

npm install react-simpple-virtualized-select-box@latest

## Using

Simple use

```jsx
<SelectBox onSelected={console.log} data={[{ id: 1, value: 'test' }]} />
```

You can use follow props

```js
itemHeight: number; // height of item in popup
showItemsCount: number; // count visible items in popup
mix: string; // mix class for main container
popupMix: string; // mix class for popup container
id: string; // id for popup
```

## Notes for using repo

Code of the npm package is placed in `/src/package`

If you try work with it and try publish or npm start you must remove unnecessary node_modules and lib of package.
