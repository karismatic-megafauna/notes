# [Anti-Patterns](https://addyosmani.com/resources/essentialjsdesignpatterns/book/#antipatterns)

Coined by Andrew Koenig in the November C++ Report and was inspired by GoF's Design Patterns book.

Good quote for Alexander (architect dude)
> “These notes are about the process of design; the process of inventing physical things which display a new physical order, organization, form, in response to function.…every design problem begins with an effort to achieve fitness between two entities: the form in question and its context. The form is the solution to the problem; the context defines the problem”.

The part I like is:
> The form is the solution to the problem; the context defines the problem.

Good and Bad are relative - a 'perfect' design may qualify as an anti-pattern
if applied in the wrong context

Bigger challenges happen after an application has hit production and is ready to go
into maintenance mode.

Examples of anti-patterns in JS:
- Polluting the global namespace
- Passing strings rather than functions to setTimeout or setInterval (triggers eval())
- Modifying the `Object` class prototype
- Using Javascript in an inline form
- Using document.write when you should use document.createElement

# Understanding
10/10. I am very familiar with antipatterns :(
