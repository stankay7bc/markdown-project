# (NOT YET & NOT QUITE) A MARKDOWN PROCESSOR

[!] This is a work in progress in the early stages of development.
The idea is to generate an html file with a nested structure that represents 
sections of a given markdown file.

## CURRENT TEXT FILE FORMATTING RULES (FOR THE SAKE OF DEVELOPMENT PROCESS)

Titles and paragraphs must be delimited by \n.

The first non-empty line must be a title and must start with a single #.
It should be the only title with a single # in the document.

All following titles must start with more than one # sign.
If a title contains more #'s than the previous, the difference should not be more than 1.

[!] Right now the script only differentiate between headings and paragraphs.

The readme.html file contained in the repository is generated by the script 
from this text as an example.

## HOW IT WORKS

Having the current version of node.js installed on your Linux system type:
: node main.js your-file.txt > output.html

## EXTERNAL REFERENCES 

- [HTML5 Outline](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/Using_HTML_sections_and_outlines#The_HTML5_outline_algorithm)


