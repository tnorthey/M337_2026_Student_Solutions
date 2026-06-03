These are my answers to Question 7(a)(i), as TikZ diagrams.

There is an A4 wrapper document:

* Q7a-i-page.tex

which includes two standalone pictures:

* Q7a-i-orientation.tex
* Q7a-i-sketches.tex

They share a preamble, tikz/tikz-preamble.tex, which contains styles and macros.

\LayoutGrid is very useful if you need to adjust the sizing/layout.

These were tested with LuaLaTeX, but should work fine with other compilers.

(There are Vim fold markers and a modeline, but they're harmless!)
