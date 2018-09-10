# Trying out Multimethods

## Start a REPL
``` shell

▶ clj
Clojure 1.9.0
user=> (load "shapes/core")
user=> (in-ns 'shapes.core)
```


Then create objects with the helper methods and call area on them.

``` shell
(def r (build-rect 4 13))
(area r)
```


## Running Tests

``` shell
clojure -Atest
```


# Challenge 

* Store language strings into a map or vector of some sort
* One, Two, Three
* Uno, Dos, Tres

* Create a new entity .. language
* Create two helper functions to create a Spanish Word and an English Word
* Create a translate function to take a Spanish word and look up the English equivalent 

