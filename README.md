laxml = Less Anal XML
=====

LAXML is a layer on top of JDOM to quietly handle crap XML, including errors such as messing up the namespaces and getting casing wrong, rather than fail to return anything.

Typically any question on stack overflow along the lines of 

> the input XML for my program has some mistakes in it, how do I fix them?

usually has an answer along the lines of:

> Find the person who generated the XML and beat them senseless.

Which I've never found very satisfactory, which is why I created this library.