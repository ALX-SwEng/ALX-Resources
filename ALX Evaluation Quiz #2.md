ALX Evaluation Quiz #2
======================

* * *

**Date:** 2022-06-17

**Status:** Done

**Duration:** 49 minutes
* * *

### Responses

#### 0\. `0x13 << 1` = ?
**Score**: 1.0

* []    0x13
* []   0x12
* [x]   0x26
* []   0x4C
* []  I don't know  

#### 1\. What does this command line print?

```
    >>> a = "Hello, world!"
    >>> print(a[:5])
```    

* [x]    Hello
* []   world!
* []    orld!
* []    I don't know  

#### 2\. What is `98` in base 16?

* [x]    `0x62`
* []    `0x98`
* []    `0x96`
* []    I don't know  

#### 3\. What is the `unistd` symbolic constant for the standard input?

* [x]    STDIN\_FILENO
* []    STDOUT\_FILENO
* []    STDERR\_FILENO
* []    I don't know  

#### 4\. Without context, on Ubuntu 14.04 LTS, `write` is a(n) …

(please select all correct answers)

* [x]    executable
* [x]    system call
* [x]    library call
* []    game
* []    I don't know  

#### 5\. What is`0b001010010` in base10?

* []    81
* [x]    82
* []    83
* []    84
* []    I don't know  

#### 6\. What does this print?

```
    >>> print("My favorite line of {} is {:d}.".format("The Zen of Python", 11))
```    

* [x]    My favorite line of The Zen of Python is 11.
* []    My favorite line of T is 1.
* []    My favorite line of The Zen of Python is 1.
* []    I don't know

  

#### 7\. The following code gives this incorrect output.

Which of the following statements about what is causing the error is true? (select all valid answers)
```
    carrie@ubuntu:/debugging$ cat main.c                               
    #include <stdio.h>                                                                                 
    
    /**                                                                                                
     * main - debugging example                                                                        
     * Return: 0                                                                                       
     */                                                                                                
    int main(void)                                                                                     
    {                                                                                                  
            int i;                                                                                     
            int j;                                                                                     
    
            for (i = 0; i < 10; i++)                                                                   
            {                                                                                          
                    j = 0;                                                                             
                    while (j < 10)                                                                     
                    {                                                                                  
                            printf("%d", j);                                                           
                    }                                                                                  
                    printf("\n");                                                                      
            }                                                                                          
    
            return (0);                                                                                
    }                                                                                                  
    carrie@ubuntu:/debugging$
    

    carrie@ubuntu:/debugging$ gcc -Wall -Werror -Wextra -pedantic main.c                                                                                                  
    carrie@ubuntu:/debugging$ ./a.out
    0000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000 <...>
    ^Ccarrie@ubuntu:/debugging$
```    

* [x]    `j` never increments so it will always be less than `10`
* []    `j` is always equal to `i` so the loop will never end
* [x]    `j` never increments so it is always going to print `0`
* []    I don't know  

#### 8\. Choose the line of code to replace the comment below so the function prints a given string without a lower or uppercase `c`.

```
    >>>def no_c_print(s):
    ...    new_string = ''
    ...    for character in s:
    ...        # REPLACE THIS LINE              
    ...           new_string += character
    ...    print(new_string)
    ...
    >>> no_c_print("Characters")
    >>>haraters
```    

* [x]    `if character not in 'Cc':`
* [x]    `if character != 'c' and character != 'C':`
* []    `if character != "cC"`
* []    I don't know  

#### 9\. When I am using `O_WRONLY | O_CREAT | O_APPEND` -> the `|` are bitwise operators.

* [x]    True
* []    False
* []    I don't know

  

#### 10\. `~ 0x98 =` ?

* []    `0x66`
* [x]    `0x67`
* []    `0x68`
* []    I don't know  

#### 11\. In the `main.c` file, on what line is the first error that the compiler returns?

Look at the following code.
```
    carrie@ubuntu:/debugging$ cat main.c                                
    #include <stdio.h>                                                                                  
    
    /**                                                                                                 
     * main - debugging example                                                                         
     * Return: 0                                                                                        
     */                                                                                                 
    int main(void)                                                                                      
    {                                                                                                   
            char *hello = "Hello, World!";                                                              
    
            for (i = 0; hello[i] != '\0'; i++)                                                          
            {                                                                                           
                    printf("%c", hello[i]);                                                             
            }                                                                                           
    
            printf("\n");                                                                               
    
            return (0);                                                                                 
    }                                                                                                   
    carrie@ubuntu:/debugging$
    

    carrie@ubuntu:/debugging$ gcc -Wall -Werror -Wextra -pedantic main.
    c                                                                                                   
    main.c: In function ‘main’:                                                                         
    main.c:11:7: error: ‘i’ undeclared (first use in this function)                                     
      for (i = 0; hello[i] != '\0'; i++)                                                                
           ^                                                                                            
    main.c:11:7: note: each undeclared identifier is reported only once for each function it appears in
    main.c:9:8: error: variable ‘hello’ set but not used [-Werror=unused-but-set-variable]              
      char *hello = "Hello, World!";                                                                    
            ^                                                                                           
    cc1: all warnings being treated as errors                                                           
    carrie@ubuntu:/debugging$       
```    

* []    9
* [x]    11
* []    7
* []    I don't know  

#### 12\. What are the different steps to form an executable file from C source code?

* []    Interpretation, compilation and assembly
* [x]    Preprocessing, compilation, assembly, and linking
* []    Interpretation, assembly and compilation
* []    Compilation and linking
* []    Preprocessing and compilation
* []    I don't know  

#### 13\. Choose a statement that would complete the function that returns a string made up of `+` `n` number of times (assuming `n` > 0) .

```
    >>> def print_plus(n):
    ...         # REPLACE THIS LINE
    ...
    >>> print_plus(3)
    >>> '+++'
    >>> print_plus(4)
    >>> '++++'
```    

* [x]    `return n*'+'`
* [x]    `return '+'*n`
* []    `return ''+n`
* []    `return``+n+n+n`
* []    I don't know  

#### 14\. What is wrong with the following code?

```
    int n = 0;
    int array[5];
    int i = 5;
    
    array[n] = i;
```    

* [x]    Nothing is wrong
* []    It is impossible to declare the variable `array` this way
* []    The array `array` is not entirely initialized
* []    It is not possible to access `array[n]`
* []    I don't know  

#### 15\. What is the correct combination of `oflags` used to open a file with the mode write only, create it if it doesn’t exist and append new content at the end if it already exists?

* []    `O_WRONLY`
* []    `O_WRONLY | O_CREAT | O_EXCL`
* [x]    `O_WRONLY | O_CREAT | O_APPEND`
* []    `O_RDWR | O_CREAT | O_APPEND`
* []    I don't know
  

Copyright © 2022 ALX, All rights reserved.
