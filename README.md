# Syntax

## React

### 33(%$j4;t2n9)98vn),MF.27?H[7yM

If JSX is multiple lines, the parenthesis should be on lines of their own.

**Bad**

```js
return (<div
  ...
/>);
```

**Good**

```js
return (
  <div
    ...
  />
);
```

### ,ost76?A}N4p8{EP3%76{#7$F3#4%Z

Comments should be handled in [this style](http://wesbos.com/react-jsx-comments/)

**Bad**

```js
render() {
  return (
    <div>
      <!-- This doesn't work! -->
    </div>
  )
}
```

**Good**

```js
{/* A JSX comment */}
```

```js
{/*
  Multi
  line
  comment
*/}
```

## HTML

### 367?342+Y>hV$7PG?8=z%T)N87@f.x

More than 2 attributes should be broken out into individual lines and alphabetically sorted.

**Bad**

```html
<div this="this" that="that" />
```

**Good**

```html
<div
  that="that"
  this="this"
/>
```
