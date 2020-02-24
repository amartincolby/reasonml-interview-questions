# Hi
Welcome to the very beginnings of this repo. Its purpose is to provide questions, answers, and general discussion of how to interview and be interviewed for roles involving ReasonML.

## The, ahem, Reason
ReasonML is a unique language. Firstly, it is basically just OCaml, but not entirely. All ReasonML programs are compiled into OCaml abstract syntax trees, but not everything in OCaml is available in ReasonML. Further, certain syntactic changes can significantly alter how one visualizes working with data in ReasonML versus OCaml. For example, ```a :: b``` in OCaml as opposed to ```[a, ...b]``` in ReasonML. For this reason, interview questions for OCaml do not map over to ReasonML easily.

Secondly, ReasonML is a true general purpose language, but it was created for specific uses. This stands in contrast to another successful language that targets JavaScript transpilation: Elm. Elm was built almost entirely for building UI's, which limits its uses as a general purpose language. For example, people in the Reason community are increasingly moving their NodeJS codebases over to ReasonML. Along with that, compliments of the notable success of Facebook's ReasonML-based Messenger application, and the fact that the creator of React was also the progenitor of ReasonML, a growing number of developers are developing their React UI's entirely in ReasonML. Consequently, unlike task-specific tools or general languages, ReasonML interviews must assess a candidate's skills on ReasonML, React, Node, JavaScript, HTML, CSS, and the intersection of them all. Even in comparison to the complex world of JavaScript, this is unique in the software engineering world.

These sorts of resources are very important. Programming is not just the language, or the engineers, or the ideas; it is the companies that choose to use the technology to solve problems. Making the technical pitch is only part of moving organizations, especially large ones, in a specific direction. The logistics must also be analyzed, and as anyone who has worked at a software company knows, hiring is an _immensely_ important part of those logistics. Further, sheepishly as they might admit it, everyone who has ever interviewed has done the "_______________ interview questions" Google search ten minutes before having to give an interview. If those people find nothing in that search, the perceived viability of the technologies being targeted is negatively affected.

## Other Resources

### Hackerrank [www.hackerrank.com](http://www.hackerrank.com)
HackerRank is one of the more popular online coding sites and offers most of its problems with Erlang and Haskell, which while not perfect analogs for ReasonML, offer enough similarities to make it worth it. Where HackerRank shines is in its Functional Programming course, where _every_ question can be done in not only OCaml, but its relatives as well, including Clojure, F#, Racket, and Common Lisp.

### Leetcode [www.leetcode.com](http://www.leetcode.com)
Another very popular testing resource for American companies, Leetcode seems to be entirely focused on being a hiring pipeline  and offering testing for industrial and commodity languages. Academic or esoteric languages need not apply. That said, their questions often involve somewhat esoteric data structures which can make excellent interview questions for ReasonML.

### Codinggame [www.codinggame.com](http://www.codinggame.com)
Last but so far from least as to likely be first is CodingGame. CodingGame was founded in France, where OCaml was created, meaning that the country is a stronghold of the language. As such, it is not surprising to find that every puzzle except for a small number fo special puzzles can be solved with OCaml. Further, of all the coding sites, CodingGame is easily the most fun. It is a riot to simply solve puzzles, and since the discussions on the boards often include OCaml, it is an excellent resource for those wanting to learn and/or hire for ReasonML roles.
