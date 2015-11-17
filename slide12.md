# Doxygen Basics (VI)

***
#### Doxygen has built in commands for putting special rules for editing the output documentation
* \b bolds the next word
* \e italicizes the next word
* \c changes the font to courier (for inline code snippits)
* \n force newline

#### Some characters need to be escaped because they are used in other commands
* `\$`,`\@`,`\|`,`\%`,`\#`,`\<`,`\>`,`\~`,`\&`,`\\`

#### Beyond these rules, doxygen generates its documentation according markdown specification
There are some doxygen specific rules for markdown
* --four spaces doesn't start code blocks, use tabs
* --inline code spans such as `example` are not supported
* --numbered lists cannot include new numbers (theyre working on this one)

* Plugins exist to impliment github style markdown instead of the doxygen variety
* Doxygen won't actually output markdown or .md files, but will include html that impliments markdown
***

[Next](https://github.com/AustinCerny/CSCI582_Presentation3/blob/master/slide13.md)
[Prev](https://github.com/AustinCerny/CSCI582_Presentation3/blob/master/slide11.md)
