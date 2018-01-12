# Lab 1 (Jan 12, 2018)
## Lisp Syntax

```
(car '(1 2 3))
```
Returns the first element of the list, `1`

```
(cdr '(1 2 3))
```
Returns the elements of the list excluding the first, `2 3`

```
(setq a '((1 2) 3))
```
Assigns `a` the value `'((1 2) 3)`

```
(car (cdr (car a)))
```
Now returns `2`. This can be shortened to:
```
(cadar a)
```
Note that any combination of `car`/`cdr` can be written as a single word with alternating `a`s and `d`s between the `c` and  `r`. 