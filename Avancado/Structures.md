Large variables, which contain other variables and logic inside
Basic foundation for objects and classes

#### Usage:
- Serialization of data
	- Data object -> Multiple things
	- Better usability, you will need parts of the data to parts that can read it
- Multiple arguments through a single one
	- As we can store variables inside these structures, we can have a lot of things in them as we just pass one thing with many others inside
- Development of data structures
	- We can make graphs, lists and many things using this

### How we can apply them
- Let's say we have a point **p** 
	- `struct point p;
- And that point p is defined as:
	- ```
	  struct point {
		  int x;
		  int y;
	  };
- We can use it to store coordinates with just a single variable
	- p.x = x coordinates and p.y = y coordinates
- Thus:
	- If we want to store something inside the structure:
		- structure_name.variable_name = something

### Defining new types
- We can define completely new data types to C by using structures
- `typedef struct {} typename;
- Then we can use it to define a variable `typename varname;

### Dereference
Let's say i have the address of some structure, we can dereference it in order to modify one attribute in it.
`address->atribute