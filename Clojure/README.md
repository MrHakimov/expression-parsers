# Combinatorial suffix expression parser
Implement function `(parseObjectSuffix "expression")` to parse expression written in suffix form and function `toStringSuffix`, which returns expression converted to string format. Example:

```clojure
(toStringSuffix (parseObjectSuffix "( ( 2 x * ) 3 - )"))
```

should return `((2 * x) - 3)`.

Parsing functions should base on [combinatorial library](/Clojure/combinators.clj).
