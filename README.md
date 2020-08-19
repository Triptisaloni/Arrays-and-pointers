# Arrays-and-pointers
6.Arrays

A multi-dimensional array holds one or more arrays. 
Declaration :
datatype variable[size 1][size 2]…….[size N];

Eg. 2D 3 x 4 integer array
   int a[3][4];






Element counting always start from 0.

Eg.    int x[2][3] = {
{2, 3, 4 }, // 1st row
{8, 9, 10} // 2nd row
Cout << x[0][2] << endl;     // 0 refers to 1st row and 2 refers to 3rd element
//prints 3rd element of first row i.e 
};
// Output 4

3d Array
String var[3][6][2];


7.Pointers

A pointer is a variable which holds address as its value.
Eg.   scorePtr holds the memory location of score
int *a ;
int b = 5;
a = &b;
b = *a;

*a returns the value at that address
&b returns the address of that variable
