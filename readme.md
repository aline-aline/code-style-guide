# Code Style Guide

1. [Syntax](#)
1. [Statement](#)
1. [Comments](#)

### Syntax

Use soft-tabs with two spaces:

```css
/* good */
.btn {
    color: #fff;
}

/* bad */
.btn{
        color: #fff;
}
```

Always use double quotes:

```css
/* good */
.btn {
    background-image: url("textura.jpg");
    font-family: "Helvetica Neue", sans-serif;
}

/* bad */
.btn {
    background-image: url('textura.jpg');
    font-family: 'Helvetica Neue', sans-serif;
}
```

Insert a space before opening brackets:

```css
/* good */
.btn {
    color: #fff;
}

/* bad */
.btn{
    color: #fff;
}
```

Close the brackets in a new line:

```css
/* good */
.btn {
    color: #fff;
}

/* bad */
.btn {
    color: #fff;}
```

Insert a space after the : of the statement:

```css
/* good */
.btn {
    color: #fff;
}

/* bad */
.btn {
    color:#fff;
}
```

Always use a ; at the end of the statement:

```css
/* good */
.btn {
    color: #fff;
}

/* bad */
.btn {
    color: #fff
}
```

Always keep to one statement per line:

```css
/* good */
.nav,
.footer,
.btn {
    color: #fff;
}

/* bad */
.nav, .footer, .btn {
    color: #fff;
}
```

Separate the rules with one blank line:

```css
/* good */
.btn {
    color: #fff;
}

.nav-item {
    color: #fff;
}

/* bad */
.btn {
    color: #fff;
}
.nav-item {
    color: #fff;
}
```

Always use lower case:

```css
/* good */
.nav-item {
    color: #fff;
}

/* bad */
.Nav-item {
    color: #fff;
}
```

Use hyphens to separate the names:

```css
/* good */
.nav-item {
    color: #fff;
}

/* bad */
.nav_item {
    color: #fff;
}
```

Every time you use hexadecimal values, always use them reduced:

```css
/* good */
.nav-item {
    color: #fff;
}

/* bad */
.nav-item {
    color: #ffffff;
}
```

Do not specify units when the value equals zero:

```css
/* good */
.nav-item {
    padding: 0;
}

/* bad */
.nav-item {
    padding: 0px;
}
```

Do not use values starting with a zero:

```css
/* good */
.nav-item {
    transition: color .3s;
}

/* bad */
.nav-item {
    transition: color 0.3s;
}
```

### Statements

All the statements have to be in alphabetical order:

```css
/* good */
.btn {
    background: #000;
    color: #fff;
    display: inline-block;
    margin: 0;
    padding: 10px;
}

/* bad */
.btn {
    padding: 10px;
    background: #000;
    display: inline-block;
    color: #fff;
    margin: 0;
}
```

### Comments

```css
/* Section comment segment
========================================= */

/* Sub-section comment segment
===================== */

/* Basic comment */
```
