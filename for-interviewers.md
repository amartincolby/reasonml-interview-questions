# For Interviewers
Since your candidates will have access to these same questions, and there is arguably little value in learning how much trivia someone knows, you should choose a subset of these questions and tailor their particulars. The goal of these questions is _not_ to catch people in ignorance, which seems often to be the case with many interviewers, especially in the JavaScript world. The goal is to use these questions to tease out the boundaries of a, often nervous, person's knowledge. If the questions fail to do that, then it is the fault of the interviewers, not the candidate. Wisdom such as this is generally important, but of special importance when trying to implement an esoteric technology.

- Describe the difference between ReasonML lists and arrays
    - A list is a singly linked list. An array is a standard JavaScript array when targeting JavaScript and a fixed-size primitive array when targeting native.
- Describe the time/space complexities of a singly-linked list.
    - A singly-linked list can be of infinite size with n memory consumed
- Describe the benefits of a list over an array
    - A list can be of infinite size in both JavaScript and native since each unit of data simply points to another unit at an arbitrary position in memory. Lists can also be used 
- Describe recursion
    - Recursion is the process by which a function calls itself to decompose a data stucture into small computable pieces.
- What is the difference between a char and a string
    - A char is represented by an integer between 0 and 255. As such, chars cannot represent Unicode characters
- Describe the compilation process of ReasonML
    - ReasonML is first turned into a standard OCaml abstract syntax tree and then either transpiled into JavaScript via Bucklescript or compiled into a native binary.
- Describe a monad
    - A monad is basically the simplest possible structure for a piece of data that provides a reliable interface to that data. It is basically a wrapper.
    - Bonus points for explaining a monoid.