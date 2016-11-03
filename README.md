# Franz Lisp: A Classic Lisp Implementation from UC Berkeley

## What Is Franz Lisp?

Franz Lisp was a Lisp implementation developed at University of California,
Berkeley by students of Richard Fateman. It was developed for porting Macsyma
algebra system, an enormous Lisp application written in Maclisp, to DEC VAX-11
minicomputer. UC Berkeley distributed it with the Berkeley Software
Distribution. Franz Inc. was founded to provide commercial support of Franz
Lisp, but the company switched to Common Lisp afterward.

## License

The original code is retrived from [Franz Lisp Opus 38.93b][op38.93b] at the
[CMU AI Repository][ai]. According to the page, that is placed in the public
domain.

## A Short Guide

The `doc/` directory contains the Franz Lisp manual written in roff. The
[manual in the PDF format][manual] can be obtained at the [Software
Preservation Group][spg]'s Web site.

The `franz/` directory contains the source code of the interpreter called
`lisp`. It is mostly written in C but plain old (pre-ANSI) one. There are also
some assembly code for VAX, Motorola 68000, etc.

The `lisplib/` directory contains Lisp code that may or may not run on Franz
Lisp, from *official* basic libraries to some foreign libraries such as a port
of Flavors (an object-oriented Lisp system) and the `loop` macro. You must have
fun here! :)

The `liszt/` directory contains the source code of the compiler called `liszt`.
It is written in Franz Lisp itself. The names of franz and liszt are taken from
the Hungarian composer Franz Liszt.

The `pearl/` directory contains an implementation of PEARL (Package for
Efficient Access to Representations in Lisp) AI programming language that was
developed by Michael Deering and Joseph Faletti at the Berkeley AI Research
Project (BAIR). Some information is available at the [Michael Deering's Web
page about PEARL][pearl].

The `utils/` directory contains some utilities used by the original developers.

[ai]: http://www.cs.cmu.edu/afs/cs.cmu.edu/project/ai-repository/ai/0.html
[manual]: http://www.softwarepreservation.org/projects/LISP/franz/Franz_Lisp_July_1983.pdf
[op38.93b]: http://www.cs.cmu.edu/afs/cs/project/ai-repository/ai/lang/others/franzlsp/op38_93b/0.html
[pearl]: http://michaelfrankdeering.com/Projects/AI/PEARL/PEARL.html
[spg]: http://www.softwarepreservation.org/
