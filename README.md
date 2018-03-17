LightOO
=======

A lightweight library for Object Oriented programming (OOP) in Haskell. 

The library is inspired by the "Mutable Objects, with tail-polymorphism" approach as described in the ["Haskell's overlooked object system"][1] paper and extends it with:

* Generic up and downcasts using dynamic typing
* An inheritance combinator, from [A Denotational Semantics of Inheritance and its Correctness][2]
* Parameterized classes
* CPP macros for deriving parts of the boilerplate

It was created as part of my master thesis ["wxHaskell for the web, 2012"][3] where it served as a tool to facilitate the implementation of an object-oriented GUI toolkit in Haskell. 

Please look inside the `src/Examples` directory for additional examples. 

Usage GHC
-------

    make ghci 

or 

    make ghci MAIN=src/Examples/{One of the examples}

Usage UHC
---------

Make sure the UHC environment variable points to your local UHC installation.

    make 

or

    make MAIN=src/Examples/{One of the examples}

[1]: https://arxiv.org/abs/cs/0509027
[2]: http://citeseerx.ist.psu.edu/viewdoc/summary?doi=10.1.1.11.8792
[3]: http://citeseerx.ist.psu.edu/viewdoc/summary?doi=10.1.1.343.134
