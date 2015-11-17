# Advanced Doxygen Usage (II)

***
#### Doxygen has mechanisms for grouping certain comments together instead of simply having them reference nearby code blocks.
#### Modules are used to create new pages for certain types categories of comments (ex function output, parameters or outputs)
* a new group is created by adding a `\defgroup` command inside a doxygen comment block followed by a unique label for the group
* blocks of comments can be added to these groups using special commands begining with the @ingroup followed by the group label
* lines that begin with  `@ingroup globals` will be placed in an separate page titled globals in the output HTML files.
***

[Next](https://github.com/AustinCerny/CSCI582_Presentation3/blob/master/slide15.md)
[Prev](https://github.com/AustinCerny/CSCI582_Presentation3/blob/master/slide13.md)
