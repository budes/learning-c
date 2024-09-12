When we talk about collateral effects in values we need to modify the **real** value, not it's value, but itself.

When we pass as an argument the pointer of a value, the function itself can modify it.
The thing works normally with arrays because it is basically a point in memory that, sequentially, stores multiple values.
So we are basically passing an address already.

### To summarize it: 
Functions (arguments) 

If we pass a value to the pointer -> Only able to manipulate the value
If we pass a pointer to the argument -> Able to manipulate the variable itself

The same thing works with structures too
