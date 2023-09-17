# Syntax
## Structure

### Variables
```nim
var name = variable;
```
#### String
```nim
var foo = "string"
```

### Conditions
Operators have natural language and symbolic options.
```nim
==    !=        and     or
is    is not    and     or
```

### Function definition
```nim
func funcName(params) : returnType
{

}

```

### Collection
_Not implemented yet_
```nim
var list = []
```

```nim
list[index]
```

### Comments
Comments are multiline by default. Everything between `//` and `;` is treated as a comment.
```cs
// This is a comment;
```

## Control Flow Statements
### Conditions
Using an operator from: `==, !=, <, <=, >, >=`. Double statements using `and` and `or`
```nim
variable == true
variabel == false
```
### If Statements

```nim
if condition
{
    //then body;
}
```

```nim
elif condition
{
    //then body;
}
```

```nim
else
{
    //then body;
}
```

### For Loop

```nim
for var name = int to int
{
    //then body;
}
```

```nim
foreach(var item in list)
{
    //then body;
}
```

### While Loop

```nim
while condition
{
    //then body;
}
```

## Functions
### Importing extern functions
```nim
extern Standard.Terminal.Print;

func main()
{
    Print("Hello World!");
}
```