# markdown-css

my attempt at developing decent css themes for styling the html documents generated by pandoc from markdown files

#### work in progress

I will add style for different elements as I come across them 


# linking css in pandoc
if you are interested in figuring out how to link a css file to pandoc for static site generation here is the syntax for pandoc (should work in both windows and linux)

``
path\to\file.md> pandoc -t html5 --css main.css --toc file.md -s -o file.html
``

one can ommit ```-t html5``` and ```-s``` if they wish 

note that the .css file has to be in the same directory as the .md file 