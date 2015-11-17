# Doxygen Output (III)

***
#### For each file, doxygen list the dependencies, the brief descriptions of its members and a detailed description of the file itself.
#### Then, the file contains XML elements of each member of the file
The following code
```
/**
Compute and return the number of digits in a positive integer.
@return The number of digits in n.
@param n An integer, the number of whose digits is desired.
@pre n contains a positive integer.
This is some other precondition, and note that it does not start on a new line.
@post
The number of digits in n has been returned.
\n This is some other post condition, and note that it does start on a new line.
*/
int numberOfDigits(int n)
{
int count = 0;
while (n != 0){
n /= 10;
++count;
}
return count;
}
```
Generates the following output
![Alt text](https://github.com/AustinCerny/CSCI582_Presentation3/blob/master/x_snip4.PNG)

***

[Next](https://github.com/AustinCerny/CSCI582_Presentation3/blob/master/slide19.md)
[Prev](https://github.com/AustinCerny/CSCI582_Presentation3/blob/master/slide17.md)
