# Standard.Terminal

Standard.Terminal is a library of functions for interacting with the terminal. 

## Contents
- [Functions](#functions)
    - [Standard.Terminal.Print](#standardterminalprint)
    - [Standard.Terminal.PrintLine](#standardterminalprintline)
    - [Standard.Terminal.Read](#standardterminalread)
- [Notes](#notes)
## Functions

### Standard.Terminal.Print

|  |  |
|-|-|
| **Description** | Prints a string to the terminal. |
| **Syntax** | Print(_string_, _string_..) |
| **Parameters** | _string_ - Any number of strings to print to the terminal. |
| **Return Value** | The values printed to the terminal. |

#### Example

```nim
Print("Hello ")
Print("World!")
```

```powershell
Hello World!
```

### Standard.Terminal.PrintLine

|  |  |
|-|-|
| **Description** | Prints a string to the terminal, followed by a newline. |
| **Syntax** | PrintLine(_string_, _string_..) |
| **Parameters** | _string_ - Any number of strings to print to the terminal. |
| **Return Value** | The values printed to the terminal. |

#### Example
```nim
PrintLine("Hello, World!")

PrintLine("Hello, ", "World!")

PrintLine("Hello, ", "World!", "!")
```

```powershell
Hello, World!
Hello, World!
Hello, World!!
```

### Standard.Terminal.Read

|  |  |
|-|-|
| **Description** | Reads a string from the terminal. |
| **Syntax** | Read() |
| **Parameters** | The line to write to the terminal before reading. |
| **Return Value** | The string read from the terminal. |

#### Example

```nim
Read("Enter your name: ")
```

```powershell
Enter your name: 
```

## Notes

_{Notes}_

