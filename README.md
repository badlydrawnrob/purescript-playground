# Purescript Playground

> By the time you get to Chapter 3.1 there's quite a lot that won't work in Elm.
> It's also highly detailed in an academic sense, so is for the serious programmer.
> For example `∀` forall type signature; `case _ of` wildcard point-free notation.
> There's quite a bit that's transferable but is mixed in with stuff that isn't.

I'm probably going to bail on this book, but might zip through it and see if there's enough examples that can be mimicked with Elm. I don't have the patience (or motivation) to be learning a "proper" Haskell-like language with all it's intricacies and quirks, and prefer a simpler setup like Elm or Racket. I'm just not interested in learning programming to that level.

## My basic goal(s)

1. To be able to write good Elm code.
2. To be able to teach basic/intermediate programming.
3. To build a prototype with simple data.[^1]
4. To validate simple business models and make money.
5. To make enough money to make good art.
6. To potentially make code as art with a book.

I'm not interested in:

- Re-learning recursion (unless it's simple stuff).
- Deep level knowledge like writing `.map` functions from scratch.
- To deal with low-level detail or database admin type stuff.


## Intro

> It was either Purescript or OCaml!
> Consider using [`htmx`](https://www.youtube.com/watch?v=3nSDA0Nd_0I) instead ☺️

Taking a spin with "[Functional Programming Made Easier](https://discourse.purescript.org/t/new-purescript-book-functional-programming-made-easier/2390/11)" book, which _says_ it's not too maths heavy, but it's already using flippin' maths notation. Purescript is NOT popular, but it might be the closest thing to Haskell and Elm Lang, so _I think_ it's worth familiarising myself with, and hope that there's enough transferable knowledge to [Lisp](https://htdp.org/2024-8-20/Book/part_two.html)[^2], [Gleam](https://gleam.run/), and other langs.

However, looking at the [Haskell operators](https://tech.fpcomplete.com/haskell/tutorial/operators/), I think it might be too much of an arse to learn.


## Tips

> See the "Functional Programming Made Easier" book for project setup guide: Part 1, Chapter 4.

1. `npx spago repl` to start
2. [`:paste`](https://stackoverflow.com/questions/60594693/purescript-how-to-define-function-signature-in-repl) for multiple lines of code
3. Problems with packages? Probably need to [install them](https://stackoverflow.com/questions/31929406/unknown-module-data-list-in-psci#comment121794172_32004727) (with spago)



[^1]: Light, and I MEAN light, data structures and backend only if absolutely necessary. I only really want to learn things like SQL to a level whereby I could run some queries for customer data. I'm not in the business of creating databases from scratch, or dealing with heavy APIs. It's basic prototypes that are _fun_ to work with, and hiring for serious work.

[^2]: Some day I need to whizz through the rest of this book (see GitHub: I think I completed more than what's saved but I'm uncertain). Clojure or other lisp langs may be something to contend with in future (but remember I'm not a proper programmer!)
