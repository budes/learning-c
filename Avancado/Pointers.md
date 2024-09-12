- An integer that points to an memory address that is holding some value
- Pointer -> Value 
	- It does not hold any value other to the address of memory the value is located at
- Can point to multiple values at once
	- `char * name` -> pointing to many `char type` values
	- name points to the first char, and then the other, and the other, **sequentially** -> That's why we can access multiple values using this pointer
		- char * name = "Samuel" -> char[0] -> char[1] -> char[2] -> ... -> `\0` (terminator)

#### Dereferencing
- `*pointer` -> value in the pointer
- Let's say we have an `int x = 5`
- If we get it's pointer using `&x` and store it in a `int * pointer`
- We can dereference it by applying `*pointer`
- Properties:
	- By having the pointer you have the value
	- You can mess with the value in it's own
	- Same properties as the value would have
