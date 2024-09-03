Types of variables
- For numbers only
	- **int**, **short**, **long**, **long long**
	- These are just positive -> **unsigned int**, **unsigned short**, **unsigned long**, **unsigned long long**
		- Unsigned = Sem nenhum sinal, positivo ou negativo
	- **float**, **double**
- Characters, numbers or not
	- **char**, **unsigned char**
- Structures

In C we don't have Boolean, so we need to define it
- In order to define something -> `#define something something`
- To define Bool:
	- ```#define BOOL char
	  #define FALSE 0
	  #define TRUE 1```
	- And that, ladies and gentleman, is how we define bool in C

To define variables
- `type name` or `type name = value`
- Something can be declared as variable even though it doesn't hold any value
- Another way to define, for many variables: `type varA, varB, varC`
- And they can hold each one different values `type varA = v1, varB = v2, varC = v3

To format something inside another thing, like to print a variable inside a string in a non-goofy way: `printf("message %format_specifier", variable)
- There's a format specifier for everything you want to print, so, in order to print them, you need to know the adequate format specifier for it
- The most important ones for now:
	- %d or %i, for decimal integers -> 1, 3, -124 or 5135135
	- %f, %Lf (the last one is for bigger floats) for float -> 1.232, 1,2414, -12214,1442
	-  %ld, %ldd, %lu, %llu are for better precision of decimal digits, signed or not
	- %c for characters -> "a"
	- %s for strings of characters -> "abc"
