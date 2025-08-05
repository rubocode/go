> [introduction](./)

![banner](/go/photos/banner.png)

## History

> Great designs come from great designers, not from great design processes.  
> **Frederick P. Brooks, Jr.**

The foundation for modern programming was laid at Bell Laboratories
by Dennis Ritchie and Ken Thompson with the creation of the
_C_ programming language and the _UNIX_ operating system.

The C programming language was essentially an abstract representation
of hardware registers in variables, combinations of those variables
in structures and the functions that could operate on them.
The syntax was the minimal necessary.
The language essentially supported structured systems programming.

![pdp-11](/go/photos/pdp-11.png)

> **Photo**: Dennis Ritchie ([INTJ](/mbti/types/intj)) and
> Ken Thompson ([INTP](/mbti/types/intp)) with the PDP-11 at
> Bell Laboratories (1972).  
> I had the privilege of visiting Bell Laboratories in Murray Hill,
> New Jersey > during my undergraduate years at Stevens Institute
> of Technology in Hoboken, New Jersey.

When the ideas of object oriented programming were desired by
another Bell Laboratories research project undertaken by
Bjarne Stroustrup ([INTP](/mbti/types/intp)), he introduced notions
in Simula into what he called C with Classes.
This project evolved into the C++ programming language.

C++ — however — never became feature-complete.  Its standardization
was delegated to a committee and they often took too long to agree
on improvements.  While there were a few significant conceptual leaps,
the committee is stuck trying to introduce modern syntax from other
languages into C++ with a new standard every 3 years.
After more than three decades of language development,
this is not a recipe for a stable and conceptually unified language.

Google founders Larry Page ([INTP](/mbti/types/intp)) and
Sergey Brin ([INTP](/mbti/types/intp)) had used C++ in the early nineties
to develop their search engine.  This resulted in the most significant
work at Google being done in C++.  But for the reasons mentioned above,
C++ became cumbersome to maintain.  It was also difficult for even the
experts to keep up with the volatility of the standard.
Google decided to create a new language well suited for their
backend processes.

They went back to Bell Laboratories legends Ken Thompson and Rob Pike
for assistance.  They added Robert Griesemer of HotJava fame into the team.
They created the Go programming language.  It was a minimalist design.
They intentionally avoided the pitfalls of C++.
The language was meant to be simple, yet sophisticated.
They focused on the stability and the quality of the design.
It  was intended to make better use of modern multicore CPU architectures.

You can look at the Go programming language as the minimalist successor
to the C programming language.  Ken Thompson is the common link in these
two endeavors.  Now we have an elegant set of abstractions on top of what
C used to provide.  These include packaging and modularization complemented
with design mechanisms for composition based integration.
