Strings are an array of characters (`char`)

We can create an string using pointers or arrays:
- Pointers: `char * name = "thing"` -> Read-only
- Array: `char name[] = "thing"

Using an `[]` makes the computer be ready to whatever is thrown at him, but you can define a size normally.
 - If you add the size, you have to compensate + 1 -> The of the string is indicated previously, and we need to put it in there in order to the computer be able to understand the end of it.

**strlen()** -> Returns the length of a string (int)
**strncmp(string1, string2, max_comparison_size)** -> Compares 2 strings
- There's also **strcmp()** which is unsafe and not recommended to use
**strncat(destination, source, n)** -> Adds the first n characters from source to the destination string 
- n = min(n, len(string)) -> Whatever is less, if it's greater than len(), it uses len

