
Lisp1
====

Lisp1 is an ANSI Common Lisp program that makes Common Lisp systems operate as a LISP1 Lisp dialects with virtually no overhead.  LISP1 means that functions are treated just like variable values.  They are in the same namespace so they can be assigned to, passed around, and localized just like variables.  No special functions or added complexity is needed.  (Scheme is a LISP1 Lisp.)

Note that Common Lisp has several namespaces.  This system collapses only the function and variable namespaces into one.  This often eliminates the need the Common Lisp functions such as function, funcall, & flet.


