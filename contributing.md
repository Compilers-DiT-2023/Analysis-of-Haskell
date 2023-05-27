# Contributing Guidelines

# Table of Contents

1.  [Tasks](#orgb1c93e8)
2.  [Citations/References](#org24dbcc4)
3.  [Index](#orgad7fc57)
4.  [Submitting](#orgaaa51fa)



<a id="orgb1c93e8"></a>

# Tasks

Every section and every chapter should be divided and organized in small enough pieces, such that each one can be realistically done by one person. So instead of someone researching a broad topic about the language and writing something about it, expecting the other person to continue right after, one should write a complete, self-contained paragraph/sub-section. That way the tasks are clearer and the parts of the report are compartmentalized, and no two people work unknowingly on the same thing. 


<a id="org24dbcc4"></a>

# Citations/References

When you use something that you found somewhere specific, include alongside the information/text/paragraph/image/anything the source/reference of it. For example:

Let&rsquo;s say that you submit the following paragraph. The first sentence&rsquo;s source is right after the sentence itself. Specifically, it is enclosed in triple curly braces (`{{{source}}}`).

    In early versions of Haskell up until and including version 1.2, user
    interaction and IO (input and output) were handled by both streams
    based and continuation based mechanisms which were widely considered
    unsatisfactory {{{Peyton Jones, Simon (2003). "Wearing the hair shirt:
    a retrospective on Haskell"
    [https://www.microsoft.com/en-us/research/publication/wearing-hair-shirt-retrospective-haskell-2003/]}}}. In
    version 1.3, monadic IO was introduced, along with the generalisation
    of type classes to higher kinds (type constructors). Along with "do
    notation", which provides syntactic sugar for the Monad type class,
    this gave Haskell an effect system that maintained referential
    transparency and was convenient

This practice must be maintained throughout the text for uniformity and simplicity.

Inside the braces you should include any relevant information for the source (e.g. for a book: the title, the author, the publishing year, the publisher, the isbn if there is one, any link that might be useful etc.)<sup><a id="fnr.1" class="footref" href="#fn.1" role="doc-backlink">1</a></sup>, for the maintainers to be able to find the source easily.


<a id="orgad7fc57"></a>

# Index

Anytime you stumble upon a new concept while you&rsquo;re writing and you see fit that it should be included in the [Index](https://en.wikipedia.org/wiki/Index_(publishing)), in a new line add a &ldquo;comment&rdquo; like so:

    In early versions of Haskell up until and including version 1.2, user
    interaction and IO (input and output) were handled by both streams
    based and continuation based mechanisms which were widely considered
    unsatisfactory. In version 1.3, monadic IO was introduced, along with
    the generalisation of type classes to higher kinds (type constructors).
    # index: type constructors
    Along with "do notation", which provides syntactic sugar for the Monad
    type class, this gave Haskell an effect system that maintained
    referential transparency and was convenient

In the 6th line, we introduce the concept of type constructors.


<a id="orgaaa51fa"></a>

# Submitting

I suggest that anytime someone wants to submit a part of the project, they should make a pull request (PR) on the repository of the project. This makes the workflow clearer and more streamlined, both for the submitters and the typesetters.

(Up for debate).


# Footnotes

<sup><a id="fn.1" href="#fnr.1">1</a></sup> If you cite a pdf file that you have available, you should send the pdf as well.
