## Q1. 得意なプログラミング言語 Favorite Programming Language
あなたの得意なプログラミング言語を記載してみてください。
Write what your favorite programming language is here.

- C
- C++


## Q2. コードの説明 Code Explanation
あなたのコードがどのように動作するのか、簡潔に説明してください。
Write a brief explanation about how your code works here.


``` C 
#include <iostream>
using namespace std;

int main(int argc, char *argv[])
{
  // start from 1 to ignore script name; argv[0] will be a name of processing file.
  for (int i = 1; i < argc; i++) {
    printf ("Hello %s!\n", argv[i]);
  }
  return 0;
}

```