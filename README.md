# the_manual
style guide and production manual

## GitHub

Getting started guides https://guides.github.com/

### Covers and Scribus

Download Scribus 1.4.6 https://www.scribus.net/scribus-1-4-6-released/

Install fonts. Once you have dowloaded the repository you will find these fonts locally  https://github.com/mrchristian/hazards/tree/master/fonts

Note: cover items are in layers, so you need to be on the right layer to edit

### Book Block .docx to .html

Install pandoc software http://pandoc.org/

Clean word processing file using Pepito Cleaner 0.1.16 plugin in LibreOffice http://pepitoweb.altervista.org/pepito_cleaner/index.php

Remove all erroneous items, also make use of the navigator function to find items;

- double spaces
- empty paras
- spaces at end of lines
- check style use
- spell check
- make sure doc in correct language
- place all links
- use styles on headers and block quotes

Include all URLs and e-mail links

Remove all underlines and colour formatting on links, this prevents underline being read as italic by pandoc

Then run pandoc script in your docs directory: pandoc -s filename.docx -o filename.html

The everything inside, but not including the body tags, can be copy pasted into your main XHTML layout doc



