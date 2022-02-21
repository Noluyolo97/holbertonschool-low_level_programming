Write a function that fills memory with a constant byte.
Prototype: char *_memset(char *s, char b, unsigned int n);
The _memset() function fills the first n bytes of the memory area pointed to by s with the constant byte b
Returns a pointer to the memory area s

Write a function that copies memory area.
Prototype: char *_memcpy(char *dest, char *src, unsigned int n);
The _memcpy() function copies n bytes from memory area src to memory area dest
Returns a pointer to dest

Write a function that locates a character in a string.
Prototype: char *_strchr(char *s, char c);
Returns a pointer to the first occurrence of the character c in the string s, or NULL if the character is not found

Write a function that gets the length of a prefix substring.
Prototype: unsigned int _strspn(char *s, char *accept);
Returns the number of bytes in the initial segment of s which consist only of bytes from accept

Write a function that searches a string for any of a set of bytes.
Prototype: char *_strpbrk(char *s, char *accept);
The _strpbrk() function locates the first occurrence in the string s of any of the bytes in the string accept
Returns a pointer to the byte in s that matches one of the bytes in accept, or NULL if no such byte is found

Write a function that locates a substring.
Prototype: char *_strstr(char *haystack, char *needle);
The _strstr() function finds the first occurrence of the substring needle in the string haystack. The terminating null bytes (\0) are not compared
Returns a pointer to the beginning of the located substring, or NULL if the substring is not found.

Write a function that prints the chessboard.
Prototype: void print_chessboard(char (*a)[8]);

Write a function that prints the sum of the two diagonals of a square matrix of integers.
Prototype: void print_diagsums(int *a, int size);
Format: see example
You are allowed to use the standard library
