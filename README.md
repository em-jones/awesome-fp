# awesome-fp
Resources I've found helpful for learning FP and examples

## Tips
**NOTE**: Don't worry too much about keeping the theory terminology straight. It's less important that you can differentiate between
a functor and a monoid, and more important that you know how to work with the data
- Learn the theory
  - Listen to the [Lamdbda Cast](https://soundcloud.com/lambda-cast) - The first two episodes, I think, should be first on your list - good for context
  and setting expectations - hosted by the author of GitKraken
  - Start with some good articles
    - [Things I wish someone had explained about functional programming](https://jrsinclair.com/articles/2019/what-i-wish-someone-had-explained-about-functional-programming/)
  - Use libraries in your work that utilize FP theory
  - Learn the primatives/patterns and their interfaces, and how to use them for patterns
    - Partial Application
    - Currying
    - Functions as types
    - Arity
    - Higher-order functions
    - Maybe / Either / Nothing
    - map(`.Select`)/fold(`.Aggregate`)/filter(`.Where`)
    - Imperative vs. Declarative programming

## Free Time Projects

Free time learning: Learn a functional language and use it to build something. I think that Elm on the Front end, and
Elixir on the back end are great ways to go. 

- [Learn elm](https://exercism.io/my/tracks/elm) / [F#](https://exercism.io/my/tracks/fsharp) + [Elmish](https://elmish.github.io/elmish/)
  - The UI is a great place to learn and apply FP principles
  - Use it to build a really simple SPA
- [Learn Elixir](https://exercism.io/my/tracks/elixir)
  - [Phoenix](https://www.phoenixframework.org/) - use elixir to build a really simple backend application 
  - [Chatbot](https://github.com/hedwig-im/hedwig) - use elixir to create a slack bot
- [Functional Programming in Erlang](https://www.futurelearn.com/courses/functional-programming-erlang)
  
## Work Time tools  
- Start using FP libraries/APIs in the code you're working on
  - [C# Language Extension](https://github.com/louthy/language-ext)
    - I feel like a lot of my FP learning came from working in angular because using `Observable` types for `Reactive`
    programming benefits greatly from FP. This language extension provides C# types and APIs for doing similar work
  - [Ramda](https://ramdajs.com/repl/?v=0.27.0)
    - I'm starting to use ramda for modularizing/abstracting repeated tasks
    
