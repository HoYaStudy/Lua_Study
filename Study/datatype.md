# Data Type

Lua's data type has 8 primitive types.

* nil
* boolean
* number
* string
* userdata
* function
* thread
* table

> `type()` function returns a string.

## String

You can get the length of the string with prefix operator `#`.

You can use `'` and `"` mixed.

`[[` can be used to hold paragraph strings. You can use paragraph string like `[=[`. Lua lexical analyzer ignores square bracket pairs with different `=` counts.

Lua supports automatic conversion between numbers and strings at run time. To convert explicitly, use the `tonumber()` or `tostring()` functions.

`..` is a concatenation operator. When used after a number, you must add a space. Otherwise, it is recognized as a decimal point.

### Escape Character

* `\a` : bell
* `\b` : backspace
* `\f` : form feed
* `\n` : line feed
* `\r` : carriage return
* `\t` : horizontal tab
* `\v` : vertical tab
* `\z` : ignore all trailing white space
* `\\` : back slash
* `\'` : single quote
* `\"` : double quote
* `\ddd`
* `\xhh`

## Table

Lua's table is an object. You can create a table using a constructor expression represented by `{}`.

It is customary for Lua's array to start at 1.

You can get the length of a sequence using the `#` operator.
