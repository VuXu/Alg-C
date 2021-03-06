Alg-C
=====

Algorithms in C/C++

gcc mycode.c

c++ mycode.c++

gcc mycode.cpp -lstdc++

If c++ file does not have the main function (declared in another file), instead of: 

c++ mycode.cpp

Try: 

g++ -c mycode.cpp
g++ -c codethathasmain.cpp
Link with
g++ -omy_program codethathasmain.o mycode.o


C#
Unlike C++, there are no object (.obj) files created as a result of invoking the C# compiler
Output files are created directly, so the C# compiler does not need a linker.

csc File.cs (=> File.exe)
csc /out:MyFile.exe File.cs (=> MyFile.exe)

to create dll (dynamically linked library):
csc /target:library File.cs



===
Creating dynamically sized arrays at run-time is done using std::vector<T>

//sizeof(i) returns the amount of memory (in bytes) for the variable or type i
//sizeof an array is the distance between elements of that array	


+[Box2D](https://github.com/erincatto/Box2D/commits/master) -  2D physics engine for games
+[Liquid Fun](http://google.github.io/liquidfun/) - 2D rigid-body and fluid simulation libraries based on Box2D


[Standard C++ Library reference](http://www.cplusplus.com/reference/iostream/cout/)

unrecognized command line option "-std=gnu++0x"
GCC 4.2 is ancient, but Apple don't ship a newer version.

You can either install a modern GCC from somewhere like Mac Ports 
(which is probably simpler and quicker) or build it yourself following the instructions 
at http://gcc.gnu.org/wiki/InstallingGCC
brew tap homebrew/versions && brew install gcc48


Basic Data Structures:
1. [STACKS](HASH/stack.cpp)
2. [QUEUES](HASH/queue.c%2B%2B)
3. LINKED LISTS
4. BINARY TREES

* [C++ cheet sheet](https://github.com/jwasham/coding-interview-university/blob/master/extras/cheat%20sheets/Cpp_reference.pdf)
* [Reference](http://en.cppreference.com/w/)
* [Coding Interview University](https://github.com/jwasham/coding-interview-university/blob/master/programming-language-resources.md)

### What not to do: 
+use malloc to dynamically allocate memory, and free to deallocate it. 
+malloc takes a count of bytes and returns a void pointer

+[coding guidelines](https://howardhinnant.github.io/coding_guidelines.html)

* Stroustrup's ["The C++ Programming Language" ](http://www.stroustrup.com/4th.html) 
* [C++ video lectures](https://www.youtube.com/user/BoQianTheProgrammer/playlists)
* [Teach yourself programming](http://norvig.com/21-days.html)
* [Recommendations about coding in C++](https://software.intel.com/en-us/articles/the-ultimate-question-of-programming-refactoring-and-everything): pay attention
* [C++ Coding Standards](http://www.informit.com/articles/article.aspx?p=373339)


