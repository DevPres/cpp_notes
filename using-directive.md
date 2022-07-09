# Using  Directive

```c++
using std::cout; // program uses cout
using std::cin; // program uses cin
```

are using declarations that eliminate the need to repeat the std:: prefix as we did in earlier programs. We can now write cout instead of std::cout and cin instead of std::cin in the remainder of the program.

```c++
using namespace std;
```

which enables your program to use names from the std namespace without the std:: qualification. In the early chapters, we’ll use this directive in our programs to simplify the code.
