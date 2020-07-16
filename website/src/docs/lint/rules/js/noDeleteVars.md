---
title: Lint Rule js/noDeleteVars
layout: layouts/page.njk
description: MISSING DOCUMENTATION
eleventyNavigation: {
	key: lint-rules/js/noDeleteVars,
	parent: lint-rules,
	title: js/noDeleteVars
}
---

# js/noDeleteVars

MISSING DOCUMENTATION

<!-- EVERYTHING BELOW IS AUTOGENERATED. SEE SCRIPTS FOLDER FOR UPDATE SCRIPTS -->


## Examples
## Invalid
```typescript
const foo = 'test';
delete foo;
```
## Valid
```typescript
const arr = [['a','b','c'], [1, 2, 3]];
delete arr[0][2];
```
```typescript
const obj = {a: {b: {c: 123}}};
delete obj.a.b.c;
```
```typescript
const foo = new Set([1,2,3]);
foo.delete(1);
```