# Articles
A list of articles, essays, and presentations about software that I feel are worth reading.

## Table of Contents

- [Shortcomings of Object-Oriented Design](#shortcomings-of-object-oriented-design)

## Shortcomings of Object-Oriented Design
[table of contents](#table-of-contents)

- [Pitfalls of Object Oriented Programming](http://harmful.cat-v.org/software/OO_programming/_pdf/Pitfalls_of_Object_Oriented_Programming_GCAP_09.pdf), Tony Albrecht
  * An indictment of OOP from the perspective of performance in game and console development. The main thesis is that OOP's main optimization bottleneck is data-access speed. Memory access is getting slower as RAM sizes grow, so OOP patterns become less and less tenable for high-performance game development as time goes on. This problem is most easily solved by writing programs whose data-operations can be parallelized. 

- [Why OO Sucks](http://harmful.cat-v.org/software/OO_programming/why_oo_sucks), Joe Armstrong
  * Joe Armstrong invented Erlang, one of the most important moments in the recent history of programming language design. The article expands on his feeling that "When [he] was first introduced to the idea of OOP [he] was skeptical but didn’t know why - it just felt 'wrong'..." I spent my early engineering career laboring under exactly this sentiment.
  * > Since functions and data structures are completely different types of animal it is fundamentally incorrect to lock them up in the same cage

- [Bad Properties of OO](http://doc.cat-v.org/programming/bad_properties_of_OO), Luca Cardelli
  * A comparison of several good-making features of programming languages between "procedural" (functional) languages and object-oriented languges.
  * > Smalltalk was originally intended as a language that would be easy to learn. C++ is based on a fairly simple model, inherited from Simula, but is otherwise daunting in the complexity of its many features. Somewhere along the line something went wrong; what started as economical and uniform ("everything is an object") ended up as a baroque collection of class varieties. Java represents a healthy reaction to the complexity trend, but is more complex than many people realize.

## GraphQL

- [GraphQL and DDD: the Missing Link](https://hackernoon.com/graphql-and-ddd-the-missing-link-4e992a26b711), Robert Zhu
  * A brief comparison between GraphQL and REST API design from the perspective of domain-driven design. I'm really interested in domain-driven design, and this relationship is one of the main things that appeal to me about GraphQL. I've felt deeply confused about the domain shape of most products I've worked on. In my experience, few people have given the fundamental shape of their product space careful attention. But GraphQL makes that process much more natural and intuitive. The technology _invites_ a careful approach.
