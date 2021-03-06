# Zig itertools

[![travis](https://travis-ci.org/onebsv1/zigraph.svg?branch=master)](https://travis-ci.org/github/onebsv1/zigraph)
[![zig070](https://img.shields.io/badge/zig-0.7.0-orange)](https://ziglang.org/)

This is an attempt to port the itertools library from python to zig, in order to introduce a functional
paradigm to the language. Maintains efficiency by reducing temporary allocations, and moving through 
slices using an iterator. The library also includes some constructs such as map, filter and reduce which 
are part of the python builtin library which are essential for functional programming.

And of course, their compile time counterparts!

Suggestions and contributions are welcome.

NOTE: De-initializing the iterator is the responsibility of the user.

## Generic Iterator

## Iterators

### Min

### Max

### Reduce

### Map

### Filter

### Accumulate

### Dropwhile

### Filterfalse

### Compress

### Takewhile

## Combinatoric Iterators

### Powerset

### Permutations

#### Lexicographically ordered

#### Efficient: Heap's method

### Combinations

#### Generate from permutations

#### Twiddle

### Product

Note: The library does not support generators yet

## Sources

#### [itertools](https://docs.python.org/3/library/itertools.html#itertools-recipes)

#### Martin Heinz, [Tour of Python Itertools](https://martinheinz.dev/blog/16)

#### MITx: 6.00.2x

#### Sedgewick R, Permutation Generation Methods, Princeton University

#### [ctregex](https://github.com/alexnask/ctregex.zig) by Alex Naskos
