# Reasoning in the browser

Brow is expressed in [ISO Prolog](https://en.wikipedia.org/wiki/Prolog#ISO_Prolog):

TERM            | Examples
----------------|---------
URI             | `'<http://example.org/etc#Socrates>'`
LITERAL         | `"abc"` `"chat"-fr` `1.52` `1e-19` `pi`
VARIABLE        | `X` `_abc` `_`
LIST            | `[TERM,...]` `[TERM,...`\|`LIST]` `[]`
LINK            | `URI(TERM)` `URI(TERM,TERM)`
GRAPH           | `LINK,...`

CLAUSE          | Examples
----------------|---------
FACT            | `LINK.`
RULE            | `LINK :- GRAPH,`[`PROLOG`](http://tau-prolog.org/documentation#prolog)`.`

Brow is using [modules](https://github.com/josd/brow/tree/master/modules) from [Tau Prolog](http://tau-prolog.org/).

## Brow examples

- [Complex numbers](https://josd.github.io/brow/examples/complex.html) ([view source](https://github.com/josd/brow/blob/master/examples/complex.html))
- [Easter date](https://josd.github.io/brow/examples/easter.html) ([view source](https://github.com/josd/brow/blob/master/examples/easter.html))
- [Enigma 1225](https://josd.github.io/brow/examples/enigma1225.html) ([view source](https://github.com/josd/brow/blob/master/examples/enigma1225.html))
- [Extended deep taxonomy](https://josd.github.io/brow/examples/edt.html) ([view source](https://github.com/josd/brow/blob/master/examples/edt.html))
- [Fibonacci numbers](https://josd.github.io/brow/examples/fibonacci.html) ([view source](https://github.com/josd/brow/blob/master/examples/fibonacci.html))
- [Four color case](https://josd.github.io/brow/examples/fourcolor.html) ([view source](https://github.com/josd/brow/blob/master/examples/fourcolor.html))
- [Goal driven Parallel Sequences](https://josd.github.io/brow/examples/gps.html) ([view source](https://github.com/josd/brow/blob/master/examples/gps.html))
- [Graph traversal](https://josd.github.io/brow/examples/graph.html) ([view source](https://github.com/josd/brow/blob/master/examples/graph.html))
- [Hanoi towers](https://josd.github.io/brow/examples/hanoi.html) ([view source](https://github.com/josd/brow/blob/master/examples/hanoi.html))
- [Lee routing](https://josd.github.io/brow/examples/lee.html) ([view source](https://github.com/josd/brow/blob/master/examples/lee.html))
- [Meta-interpretation](https://josd.github.io/brow/examples/mi.html) ([view source](https://github.com/josd/brow/blob/master/examples/mi.html))
- [Padovan numbers](https://josd.github.io/brow/examples/padovan.html) ([view source](https://github.com/josd/brow/blob/master/examples/padovan.html))
- [Polynomial roots](https://josd.github.io/brow/examples/polynomial.html) ([view source](https://github.com/josd/brow/blob/master/examples/polynomial.html))
- [Socrates is a mortal](https://josd.github.io/brow/examples/socrates.html) ([view source](https://github.com/josd/brow/blob/master/examples/socrates.html))
- [Superdense coding](https://josd.github.io/brow/examples/sdcoding.html) ([view source](https://github.com/josd/brow/blob/master/examples/sdcoding.html))
- [Turing machine](https://josd.github.io/brow/examples/turing.html) ([view source](https://github.com/josd/brow/blob/master/examples/turing.html))


## Background

- Personal notes by Tim Berners-Lee: [Design Issues](https://www.w3.org/DesignIssues/)
- Book of Markus Triska: [The Power of Prolog](https://www.metalevel.at/prolog)
