# Things to add to Anki

> Or some other method of personal docs

There's quite a lot in "Functional Programming Made Easier" that's the equivalent of having the verbal shits. Technical language and maths that really don't add much (for the lay person) and confuses things. Words like "polymorphic", "coproduct", and "algabreic data types" ... for fuck sake just speak plainly.

Words like `isomorphic` _might_ be useful to know, but I feel that plain language is just nicer to deal with as a beginner. Perhaps as you progress you need this language to be able to communicate, but it feels too much like a "club" with overly pedantic jargon.

> **Isomorphic** just means that one form can be converted to the other without loss of information. So `a b c` can be converted to some other `a b c` format.

In my opinion this pedantry is why hardly anyone uses statically typed languages, and why Elm (with it's excellent compiler errors) is a step in the right direction.

## To Dos

> Never use a long word where a short one will do.
> If it is possible to cut a word out, always cut it out.
> — George Orwell

1. <s>Difference between `sum` types and `product` types (very simply put)</s>
    - <s>Basically sum types are like union (enumerated options) ...</s>
    - <s>And only hold a single variable (I think), which can be</s> a distinct type `Error String` or a type variable `Error any`
    - <s>A product type holds many variables `Triplet a b c` (there's also a record version `type Something = Something { ... }` in the book. Is _that_ a product type? Does it even matter?)</s>
    - **TL;DR** You don't necessarily need a word to describe these other than `record`, `type alias`, `types`, `type variable`, `arguments`, `constructor functions`, etc. The basic terminology serves. You can explain the parts quite succinctly and they combine together in various ways.
2. The above (I think) touches on "Set Theory" which is interesting (Unions and Intersects) but I just don't think it's necessary. You can explain combinations of sum types and product types without going into that?
    - If you _really_ want to understand it, there's books (like this one) that go heavy in on it.
    - For just getting stuff done, show some concrete storied examples that show _how they're used_ rather than highly technical explanations.
