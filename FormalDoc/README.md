# Textual

This stylesheet attempts to create a formal document from pandoc generated html.

# Use

For best results use the following arguments in pandoc: 

```bash
pandoc filename.md -to html --css Path/to/stylesheets/Textual.css -s -o outputfilename.html  
```

to ensure the desired output use # Heading as your section headings and ##, ###, etc as sub sections

# Printing

if you want to create an A4 document as a pdf please use a chromium based browser as there are currently issues with firefox (unless you ensure to tick the "Shrink to to fit" box)