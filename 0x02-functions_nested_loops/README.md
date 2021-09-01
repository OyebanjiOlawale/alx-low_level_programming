The program should return 0
0 - Write a program that prints Holberton, followed by a new line.

julien@ubuntu:~/0x02$  gcc -Wall -pedantic -Werror -Wextra -std=gnu89 _putchar.c 0-holberton.c -o 0-holberton
julien@ubuntu:~/0x02$ ./0-holberton 
Holberton
julien@ubuntu:~/0x02$ 
1 - Write a function that prints the alphabet, in lowercase, followed by a new line.

Prototype: void print_alphabet(void);
You can only use _putchar twice in your code
julien@ubuntu:~/0x02$ cat 1-main.c
#include "main.h"

/**
 * main - check the code for ALX School students.
 *
 * Return: Always 0.
 */
int main(void)
{
    print_alphabet();
    return (0);
}
julien@ubuntu:~/0x02$ gcc -Wall -pedantic -Werror -Wextra -std=gnu89 _putchar.c 1-main.c 1-alphabet.c -o 1-alphabet
julien@ubuntu:~/0x02$ ./1-alphabet 
abcdefghijklmnopqrstuvwxyz
julien@ubuntu:~/0x02$

<p>Write a function that prints 10 times the alphabet, in lowercase, followed by a new line.</p>
Prototype: void print_alphabet_x10(void);
You can only use _putchar twice in your code
