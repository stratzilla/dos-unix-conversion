# dos-unix-conversion
A simple C++ reimplementation of dos2unix and unix2dos.

Compile with: 

`$ g++ -std=c++11 d2u.cpp -o d2u`
`$ g++ -std=c++11 u2d.cpp -o u2d`

And execute with:

`$ ./d2u <arg>`
`$ ./u2d <arg>`

Where `<arg>` is the text file to convert from DOS to Unix or Unix to DOS respectively.
