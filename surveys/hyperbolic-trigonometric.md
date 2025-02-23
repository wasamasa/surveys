# Hyperbolic trigonometric functions

This is a list of systems and their support for the hyperbolic trigonometric
functions.

Also included is the result for `(atanh 1)`.

| System      | support | (atanh 1) |
|-------------|---------|-----------|
| Bigloo      | n       |           |
| Biwa        | n       |           |
| Chez        | y       | error     |
| Chibi       | n       |           |
| Chicken     | lib     | +inf.0    |
| Cyclone     | n       |           |
| Gambit      | y       | error     |
| Gauche      | y       | +inf.0    |
| Guile       | y       | +inf.0    |
| Kawa        | y       | +inf.0    |
| LIPS        | n       |           |
| Loko        | n       |           |
| MIT         | n       |           |
| Racket      | y       | +inf.0    |
| Sagittarius | n       |           |
| SCM         | y       | +inf.0    |
| STklos      | y       | error     |
| Unsyntax    | n       |           |
| Ypsilon     | n       |           |

These functions are part of the Common Lisp standard, but not all implementations work the same, as can be seen below. Clojure was also added to the list, being the only other popular Lisp that implements these functions (Emacs Lisp doesn't).

| System  | (atanh 1)                          |
|---|---|
| ABCL    | `#.SINGLE-FLOAT-POSITIVE-INFINITY` |
| CCL     | division by zero                   |
| Clisp   | division by zero                   |
| ECL     | division by zero                   |
| GCL     | division by zero                   |
| SBCL    | division by zero                   |
|         |                                    |
| Clojure | illegal argument                   |
