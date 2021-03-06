---
title: Rule no-delete-var
layout: doc
---
<!-- Note: No pull requests accepted for this file. See README.md in the root directory for details. -->

# Disallow Variables Deletion (no-delete-var)

The purpose of the `delete` operator is to remove a property from an object. Using the `delete` operator on a variable might lead to unexpected behavior.

## Rule Details

This rule prevents the use of `delete` operator on variables.

Examples of **incorrect** code for this rule:

```js
/*eslint no-delete-var: "error"*/

var x;
delete x;
```

## Further Reading

* [Only properties should be deleted](http://jslinterrors.com/only-properties-should-be-deleted/)

## Version

This rule was introduced in ESLint 0.0.9.

## Resources

* [Rule source](https://github.com/eslint/eslint/tree/master/lib/rules/no-delete-var.js)
* [Documentation source](https://github.com/eslint/eslint/tree/master/docs/rules/no-delete-var.md)
