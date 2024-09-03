for loops are really simple

`for (variable = something; condition; something_to_variable) { something }

*For* example (pun intended):
- *Red hood after reading her book thought to herself "no way i'm going to get lost in this forest", so she started counting down from the 150 meter point where she to the 75 meter point, because there was a forest guard post nearby, step by step, knowing she does 4 steps to walk a meter, she started the countdown from her steps*
- The script could be:
```
int step
for (step = 150 * 4; step > 75 * 4; step --) { printf("on step %d", step); } 
```

