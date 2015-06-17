Published Terms Preamble
========================

A standard contract preamble for agreement on published terms

A _what_?
---------

Start with a look at the [included example](./example.md).

### For lawyers

The Preamble is the first stage in a two-step process of incorporation by reference.

In the first stage, an agreement defines specific terms to refer to the parties and deal-specific terms, like security price or length of contract term. The agreement then incorporates the Preamble by reference to a secure website URL, backed by a [cryptographic fingerprint][wiki-hash] to prevent tampering.

In the second stage, the Preamble, now incorporated by reference, uses similar methods to incorporate the desired form agreement by reference. Terms defined for deal-specific terms in the body of the agreement are "passed through" to the form. The preamble also includes some rules of construction to prevent tampering with the published terms.

### For systems programmers

Think of the Preamble as a kind of [loader][wiki-loader] for form contracts. It brings terms written in a document published on the Internet into the context of a legal contract, with some integrity and authenticity checks for good measure. As a loader expects binaries of a certain format (e.g. [ELF][wiki-elf]), the Preamble expects the published form to expose a defined term-based interface. As a loader copies command-line arguments to the stack, the Preamble passes defined terms through to the published terms.

### For functional programmers

Think of the Preamble as a higher-order function that [binds][mdn-bind] the terms of a public form contract to a specific legal context. The context includes the identity of the parties making the deal and any deal-specific points they need to plug into the form. The bound function is then "applied" by signing the agreement. (Fun fact: Lawyers call the act of signing "execution".)

### For open-source programmers generally

The Preamble also works something like a source code package manager, pulling the terms of a published form contract into a contract for use between two parties.

### For finance professionals

When trading, say, futures on an exchange, agreements with the exchange and traditions in the industry provide the terms and context necessary to turn a simple confirmation or open-outcry order into a security with detailed, legally binding terms. In a private trading context, a master agreement, such as an ISDA Master Agreement between institutions, provides this context for short-form confirmations.

The Preamble allows a document as terse as a confirmation or electronic order, which states the terms of a specific deal, to create the same kind of context for itself, just for that deal. The preamble brings in the terms of a form agreement published on the Internet that uses the terms defined in the agreement and fills in the rest of the legal gaps.

[wiki-loader]: https://en.wikipedia.org/wiki/Loader_(computing)

[wiki-elf]: https://en.wikipedia.org/wiki/Executable_and_Linkable_Format

[mdn-bind]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Function/bind

[wiki-hash]: https://en.wikipedia.org/wiki/Cryptographic_hash_function
