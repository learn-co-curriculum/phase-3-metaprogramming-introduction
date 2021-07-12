# Introduction to Metaprogramming

Ruby has impressive **metaprogramming** capabilities. A traditional program is
mainly code that manipulates a data structure and produces output, but
metaprogramming allows us to essentially **write code that writes code**.
Metaprogramming is one of Ruby's most powerful features: it lets you perform
tasks in a few minutes that may take hours to do in other languages. By cleverly
planning your code and applying the techniques mentioned here, you’ll be able to
write code that is DRYer, lighter, more intuitive and more scalable.

In this section we'll be discussing and working through some metaprogramming
concepts such as:

- Mass assignment
- Keyword arguments
- Creating custom errors and using them

Ruby's metaprogramming features offer a lot of functionality. You could, in
theory, write everything from scratch yourself, but doing that is very
inefficient. In this section of lessons and labs, we'll reveal how
metaprogramming makes sense, and is very needed in many situations.

A word of caution: the code in this section will be among the most abstract that
we'll deal with to date, so don't worry if the concepts don't make sense
immediately! It takes a lot of practice and a bit of re-training your
programming brain to identify the kinds of problems that can be solved with
metaprogramming.
