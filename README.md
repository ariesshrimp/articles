# Articles
A list of articles, essays, and presentations about software that I feel are worth reading.

## Shortcomings of Object-Oriented Design

- [Pitfalls of Object Oriented Programming](http://harmful.cat-v.org/software/OO_programming/_pdf/Pitfalls_of_Object_Oriented_Programming_GCAP_09.pdf), Tony Albrecht
  * An indictment of OOP from the perspective of performance in game and console development. The main thesis is that OOP's main optimization bottleneck is data-access speed. Memory access is getting slower as RAM sizes grow, so OOP patterns become less and less tenable for high-performance game development as time goes on. This problem is most easily solved by writing programs whose data-operations can be parallelized. 

- [Why OO Sucks](http://harmful.cat-v.org/software/OO_programming/why_oo_sucks), Joe Armstrong
 * Joe Armstrong invented Erlang, one of the most important moments in the recent history of programming language design. The article expands on his feeling that "When [he] was first introduced to the idea of OOP [he] was skeptical but didn’t know why - it just felt 'wrong'..." I spent my early engineering career laboring under exactly this sentiment.
