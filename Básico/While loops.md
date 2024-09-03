`while (condition) { thing }

It will do it's thing while the condition is `true`, which means it will run indefinitely. This is basically the whole reason you would want to use this thing.

**continue** -> Whenever you use it, it will basically skip to the next iteration, which means, it is useful to skip certain parts of code.
In the example below, you'll only see the text if it's not under condition 2, because if it is, it will not print anything, as it will just skip it.
```
while(condition) {
	if (condition2) {
		continue; 
	}
	
	printf("wow, you made it");
}
```

**break** -> Whenever you use it, it will basically break the loop, you'll just exit the loop completely, stop it wherever you are.
The example below is basically, you get 2 odds, or 1 even and the game is completely over.
```
int i = 1
while(condition) {	
	if (i % 2 == 0) {
		break;
	}
	
	printf("wow, you made it");
	i += randomNum;
}
```