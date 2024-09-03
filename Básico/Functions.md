As in the main() function -> `type name ( *arguments ) {}
- The \*arguments part is any amount arguments with any type, as long as you indicate their type and name (also, it's not mandatory)

```
int power(int num) {
	return num*num
}
```
This example above is as valid as 
```
string moo() {
	return "moo"
}
```

If you do not want it to return anything -> **void**
`void name() {}
