Static -> Bigger scope

Static variables -> Everywhere in their file
Static functions -> Limited by their files, can't be imported

Static is better described as: "i belong to this neighborhood"

In variables, as they are not limited anymore to the job of their function, they will be "remembered" by the script even if the execution of the function is over, also, a variable can't be re-declared in the same scope as before, so if you declare a function or a variable with the same name, it will be ignored, as it was already declared

Variables -> `static type name = value`
Functions -> `static type name (*args) {}
