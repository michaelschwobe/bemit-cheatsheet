# BEMIT Cheatsheet

Give developers more knowledge about how the classes behave in a non-relative sense: BEM + ITCSS = BEMIT

- [More Transparent UI Code with Namespaces](http://csswizardry.com/2015/03/more-transparent-ui-code-with-namespaces/)
- [BEMIT: Taking the BEM Naming Convention a Step Further](http://csswizardry.com/2015/08/bemit-taking-the-bem-naming-convention-a-step-further/)

## Evolution

BEM:
```css
.block__element--modifier {}
```

BEM w/ Namespaces:
```css
.namespace-block__element--modifier {}
```

BEM w/ Namespaces & Responsive Suffixes:
```css
.namespace-block__element--modifier\@suffix {}
```

## Namespaces

Object
```css
.o-object-name[<element>|<modifier>] {}
```

Component
```css
.c-component-name[<element>|<modifier>] {}
```

Utility
```css
.u-utility-name {}
```

Theme
```css
.t-theme-name {}
```

Scope
```css
.s-scope-name {}
```

State
```css
.[is|has]-state {}
```

Hack
```css
._<namespace>hack-name {}
```

Javascript
```css
.js-component-name {}
```

Quality Assurance
```css
.qa-node-name {}
```

## Responsive Suffixes

Breakpoints
```css
.o-object-name\@sm {}
.o-object-name\@md {}
.o-object-name\@lg {}
```

Media type
```css
.u-utility-name\@print {}
```
