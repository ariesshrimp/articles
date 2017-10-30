# Articles, Essays, and Presentations
A list of articles, essays, and presentations about software that I feel are worth reading.

## Table of Contents

- [Shortcomings of Object-Oriented Design](#shortcomings-of-object-oriented-design)
- [GraphQL](#graphql)
- [Functional Programming](#functional-programming)
- [General Software Architecture](#general-software-architecture)
- [Workflow and Process](#workflow-and-process)

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

[table of contents](#table-of-contents)

- [GraphQL and DDD: the Missing Link](https://hackernoon.com/graphql-and-ddd-the-missing-link-4e992a26b711), Robert Zhu
  * A brief comparison between GraphQL and REST API design from the perspective of domain-driven design. I'm really interested in domain-driven design, and this relationship is one of the main things that appeal to me about GraphQL. I've felt deeply confused about the domain shape of most products I've worked on. In my experience, few people have given the fundamental shape of their product space careful attention. But GraphQL makes that process much more natural and intuitive. The technology _invites_ a careful approach.

- [GraphQL First: A better way to build modern apps](https://dev-blog.apollodata.com/graphql-first-a-better-way-to-build-modern-apps-b5a04f7121a0), Matt DeBergalis

- [Lessons learned wrapping a REST API with GraphQL](http://www.joelgriffith.net/lessons-learned-wrapping-a-rest-api-with-graphql/), Joel Griffith
  * A really clean approach to using GraphQL to automate REST service wrapping.

## Functional Programming

[table of contents](#table-of-contents)

- [Make the Leap from JavaScript to PureScript](https://hackernoon.com/make-the-leap-from-javascript-to-purescript-5b35b1c06fef), Alex Kelley
  * A truly comprehensive into pure functional programming using PureScript. This series is book length, and it dives _deep_. By article 9 the author is defining and implementing custom monoids.

- [Node server with Rx and Cycle.js](https://glebbahmutov.com/blog/node-server-with-rx-and-cycle/), Dr. Gleb Bahmutov PhD
  * A tutorial on writing pure functional reactive HTTP servers in Node.

- [Railway oriented programming](http://fsharpforfunandprofit.com/posts/recipe-part2/)

- [Partial Application is Dependency Injection](http://blog.ploeh.dk/2017/01/30/partial-application-is-dependency-injection/)

- [Object-oriented Design Patterns From a Functional Perspective](http://gorodinski.com/blog/2013/09/18/oop-patterns-from-a-functional-perspective/)

## General Software Architecture

- [Clean Code Javascript](https://github.com/ryanmcdermott/clean-code-javascript), Ryan McDermott
  * An outline of Robert Martin's _Clean Code_ priniciples using contemporary JavaScript.
  
- [A Little Architecture](http://blog.cleancoder.com/uncle-bob/2016/01/04/ALittleArchitecture.html), Robert C. Martin
  * A platonic dialogue between an aspiring software architect and an experienced one. The experienced one tries to explain what is really essential to maintainable architecture.
  * > That’s right. They are. The important decisions that a Software Architect makes are the ones that allow you to NOT make the decisions about the database, and the webserver, and the frameworks.

- [Twelve-Factor Apps in Node.js](http://peterlyons.com/twelve-factor-nodejs#/), Peter Lyons
  * A detailed discourse on implenting the [12 factor app principles](https://12factor.net/) in a `Node` project. Super useful to see Node specific explanations.  
  
- [REST APIs must be hypertext-driven](http://roy.gbiv.com/untangled/2008/rest-apis-must-be-hypertext-driven), Roy T. Felding
  * A bullet list of RESTful requirements by the original author of the REST thesis. The comment thread is also very instructive. See especially [comment #8](http://roy.gbiv.com/untangled/2008/rest-apis-must-be-hypertext-driven#comment-724)
  * > I think most people just make the mistake that it should be simple to design simple things. In reality, the effort required to design something is inversely proportional to the simplicity of the result. As architectural styles go, REST is very simple.
  
## Workflow and Process

[table of contents](#table-of-contents)

- [Github Labels and Milestones](https://docs.saltstack.com/en/latest/topics/development/labels.html)
  * SaltStack's label and milestone conventions. Lots of interesting ideas about how to organize work using Github features.

- [Speed in Software Development](https://www.targetprocess.com/articles/speed-in-software-development/), MICHAEL DUBAKOV
  * An exploration of many factors that bear on the pace of development in software, both long-term and short-term. Lots of interesting external links too.

- [Why and How to Use Docker for Development](https://medium.com/travis-on-docker/why-and-how-to-use-docker-for-development-a156c1de3b24)
