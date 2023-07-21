Why?
--

It needs no further reason or explanation. This is,

- A promotional piece for the [Cosmos](https://cosmos-lang.github.io/)™ programming language and the Space™ graphical framework.
- A groundbreaking experiment on multiparadigm programming.

This application marks an advance in multiparadigm programming language design and theory.

After all, it's probably the _first_ time tictactoe (or for that matter any graphical application has been made in at least three of the _main four_ paradigms (and then a few others),

- Logic programming.
- Functional programming.
- Object-oriented programming.
- Procedural programming(?).

Ok, so we're not sure about procedural. Procedural is the one responsible for if-statements, and there are if-statements, so you could push it but that's just redundant. No one says "_Procedural_ Object-Oriented programming". Let's forget about this one.

Open-source
--

Cosmos™, Space™ and this game is all open-source. Anyone can edit it but it's free of warranty.

Tic-tac-toe is probably on the public domain.

# Installation

- Install Cosmos 0.5+.
- Install Space.
- Place those files on the Space/ folder.

Type,

```
cosmos -l board
cosmos -l tictactoe
```

# FAQ

_How functional is this?_
--

The approach we follow is described here,
https://gamedev.stackexchange.com/questions/74015/pure-functional-programming-and-game-state

In summary, the game logic is entirely declarative, while only the _draw_ function is impure and done with side effects. It may be possible to make drawing pure, but we didn't pursue the topic.

_Why not reactive?_
--

That is actually a great idea. If it were reactive too, then this would be a _Reactive Logic-Functional Object-Oriented Prototypal Temporal_ version of tictactoe and the title would be even longer. Truly, we look forward to the day someone makes a reactive lib for the language and then we may do it. As things stand, we used the non-reactive method outlined above.

_How logic is this?_
--

It's all logic programming, in addition to functional features, thus logic-functional™. It's made in a logic language which uses another logic language as a host.

Honestly, we wanted to add some more support for constructive negation so we could brag about logic purity a bit further, but that'll have to wait for 0.6. It's also more verbose than it should be, really.

_How OOP is this?_
--

It follows the prototypal approach to OOP, except that the dictionary used for it is immutable so that it can still be logic-functional.

Incidentally, that's also how it's prototypal.

_Why not classical OOP?_
--

Then it wouldn't be prototypal, making the title a bit shorter.

We couldn't have that.

_How is this temporal?_
--

_next_ is an operator in temporal logic. Therefore, since Cosmos™ has a _next_ keyword, it is part of the temporal logic paradigm. Thus, it's not only logic-functional but _temporal logic-functional._

_That's just imperative programming!?_
--

No, it isn't. Didn't you read above?

_It can't be both OOP and functional!?_
--

What an old-fashioned way of thinking.

_I don't like OOP/logic/functional programming!?_
--

That's your opinion.
