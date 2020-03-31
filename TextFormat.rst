Styles of text and languages
============================
The format for different text and languages are stored here, see:


RST (reStructured Text)
-----------------------
.rst file is offen used for Sphnix to write docs

:0. Basics:

| Paragraphs line up at their left edges, and are separated by blank lines.

:1. Section Structure:

| Title
| \=====
| Subtitle
| \--------------

:2. Style: 

====================    ========================
Plain text              Result
====================    ========================
\*Italics*              *Italics*
\**Emphasis**           **Emphasis**
\\\**Escape**           \**Escape**
====================    ========================

:3. Line Blocks:

| Each new line begins with a vertical bar ("|"), for example:
| | First Line
| | Second Line
|
| A paragraph containing only two colons indicates that the following indented or quoted text is a literal block, for example:

| Plane text:
| \::
|
| \     We start here
| \ and end here.

| Result:

::

      We start here
  and end here.


:4. Lists:   

====================    ========================
Plain text              Result
====================    ========================
\:Version:: 1.0         :Version:: 1.0  
\* ListType1            * ListType1
\- ListType2            - ListType2 
\3. ListType3           3. ListType3
\#. ListType4            #. ListType4
====================    ========================

:5. Tables:

| For example:
|
| =====  =====
|   A      B    
| =====  ===== 
|   1      2 
|   3      4  
| =====  ===== 
|
| Result:

=====  =====
  A      B    
=====  ===== 
  1      2 
  3      4  
=====  ===== 

:6. Hyperlink:

| For example:
::

    see reference 1_:
    .. _1: https://docutils.sourceforge.io/docs/user/rst/quickref.html

| Result:

see reference 1_:

.. _1: https://docutils.sourceforge.io/docs/user/rst/quickref.html

:7. Citation Reference:

| For example:
::

    Footnote  [1]_

    .. [1] Body elements

| Result:

Footnote  [1]_

.. [1] Body elements

Reference: 

1. https://docutils.sourceforge.io/docs/user/rst/quickref.html

2. https://www.jianshu.com/p/1885d5570b37