# FunctioalProgramming

The 5 SOLID JavaScript (or any language) principles are:

----------------------------------------------------------------------------------------------------------------
S – Single Responsibility Principle
   => Every function you write should do exactly one thing. It should have one clearly defined goal.
   => You’ll be surprised at the number of times you would like your function to do more than “one thing”.
   => You’ll also struggle repeatedly with defining what the “one thing” you want to do is.
----------------------------------------------------------------------------------------------------------------
O – Open-Closed Principle
----------------------------------------------------------------------------------------------------------------
   =>Open-Closed Principle means our JavaScript modules should be open to extension, but closed to modification.
   =>Meaning that if someone wants to extend our module’s behavior, they won’t need to modify existing code if they don’t want to.
----------------------------------------------------------------------------------------------------------------
L – Liskov Substitution Principle
----------------------------------------------------------------------------------------------------------------

----------------------------------------------------------------------------------------------------------------
I – Interface Segregation Principle
----------------------------------------------------------------------------------------------------------------

----------------------------------------------------------------------------------------------------------------
D – Dependency Inversion Principle
----------------------------------------------------------------------------------------------------------------

----------------------------------------------------------------------------------------------------------------

Dry Principle
----------------------------------------------------------------------------------------------------------------
  =>Don't repeat yourself is a principle of software development aimed at reducing repetition of software patterns,
   replacing it with abstractions or using data normalization to avoid redundancy.
----------------------------------------------------------------------------------------------------------------

Functional programming principles
----------------------------------------------------------------------------------------------------------------
==>Functional programming aims to be declarative and treats applications as the 
   result of pure functions which are composed with one another.

==>The primary aim of this style of programming is to avoid the problems that come with shared state,
   mutable data and side effects which are common place in object oriented programming.

==> solving problems thru function(s)


principles :
    Functions as first-class entities
    
    i.e

    => A function can be stored in a variable or value i,e function is first-class citizen
    => A parameter of a function can be a function 
    => The return value of a function can be a function

Benefits

=>Functional programming leads to modular code. You have small functions that you can reuse over and over. 
  Knowing the specific functionality of each function means pinpointing bugs and writing tests should be straightforward,
  especially since the function outputs should be predictable.

=>In addition, if you are trying to use multiple cores, you can distribute function calls across those cores, so it can lead to more computational efficiency.    
----------------------------------------------------------------------------------------------------------------
