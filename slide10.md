# Doxygen Basics (IV)

***
#### When using doxygen, documented comments are distinguished from undocumented comments using a special escape sequence.
* In regular cpp
```
// This is a single comment

/*
	This is a comment
	that occupies multiple rows
*/

```
* In Doxygen documented comments
```
/// This is a single comment
//! This is also a single comment (there's 2 options)

/**
*	This is a comment
*	that occupies multiple rows
*/

/*!
*	This is also a comment
*	that occupies multiple rows
*/
```

#### The prefix of this escape sequence also makes it a comment in a c style language.
#### The escape sequence is different for other languages like python etc.
***

[Next](https://github.com/AustinCerny/CSCI582_Presentation3/blob/master/slide11.md)
[Prev](https://github.com/AustinCerny/CSCI582_Presentation3/blob/master/slide09.md)
