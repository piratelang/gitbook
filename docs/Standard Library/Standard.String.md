# Standard.String

Standard.String is a library of functions for working with strings.

## Contents

- [Functions](#functions)
  - [Standard.String.CharAt](#standardstringcharat)
  - [Standard.String.CharCodeAt](#standardstringcharcodeat)
  - [Standard.String.Concat](#standardstringconcat)
  - [Standard.String.IndexOf](#standardstringindexof)
  - [Standard.String.LastIndexOf](#standardstringlastindexof)
  - [Standard.String.Length](#standardstringlength)
  - [Standard.String.Split](#standardstringsplit)
- [Notes](#notes)


## Functions
### Standard.String.CharAt

|  |  |
|-|-|
| **Description** | Returns the character at the specified index in a string. |
| **Syntax** | CharAt(_string_, _index_) |
| **Parameters** | _string_ - The string to return a character from. <br> _index_ - The index of the character to return. |
| **Return Value** | The character at the specified index in the string. |

#### Example

```nim
CharAt("Hello World", 6)
```

```powershell
W
```

### Standard.String.CharCodeAt

|  |  |
|-|-|
| **Description** | Returns the Unicode value of the character at the specified index in a string. |
| **Syntax** | CharCodeAt(_string_, _index_) |
| **Parameters** | _string_ - The string to return a character from. <br> _index_ - The index of the character to return. |
| **Return Value** | The Unicode value of the character at the specified index in the string. |

#### Example

```nim
CharCodeAt("Hello World", 6)
```

```powershell
87
```


### Standard.String.Concat

|  |  |
|-|-|
| **Description** | Combines two or more strings into one string. |
| **Syntax** | Concat(_string1_, _string2_, ...) |
| **Parameters** | _string1_ - The first string to combine. <br> _string2_ - The second string to combine. <br> ... - Additional strings to combine. |
| **Return Value** | A string that is the result of combining the specified strings. |

#### Example

```nim
Concat("Hello,", " ", "World")
```

```powershell
Hello, World
```

### Standard.String.IndexOf

|  |  |
|-|-|
| **Description** | Returns the index of the first occurrence of a specified value in a string. |
| **Syntax** | IndexOf(_string_, _value_) |
| **Parameters** | _string_ - The string to search. <br> _value_ - The value to search for. |
| **Return Value** | The index of the first occurrence of the specified value in the string. |
#### Example

```nim
IndexOf("Hello World", "World")
```

```powershell
6
```
<br>

```nim
IndexOf("Hello World", "Earth")
```

```powershell
-1
```

### Standard.String.LastIndexOf

|  |  |
|-|-|
| **Description** | Returns the index of the last occurrence of a specified value in a string. |
| **Syntax** | LastIndexOf(_string_, _value_) |
| **Parameters** | _string_ - The string to search. <br> _value_ - The value to search for. |
| **Return Value** | The index of the last occurrence of the specified value in the string. |

#### Example

```nim
LastIndexOf("Hello World", "o")
```

```powershell
7
```

<br>

```nim
LastIndexOf("Hello World", "Earth")
```

```powershell
-1
```

### Standard.String.Length

|  |  |
|-|-|
| **Description** | Returns the length of a string. |
| **Syntax** | Length(_string_) |
| **Parameters** | _string_ - The string to return the length of. |
| **Return Value** | The length of the string. |

#### Example

```nim
Length("Hello World")
```

```powershell
11
```

### Standard.String.Split

|  |  |
|-|-|
| **Description** | Splits a string into an array of substrings. |
| **Syntax** | Split(_string_, _separator_) |
| **Parameters** | _string_ - The string to split. <br> _separator_ - The character or characters to use to split the string. |
| **Return Value** | A list of strings that are the substrings of the specified string. |

#### Example

```nim
Split("Hello World", " ")
```

```powershell
["Hello", "World"]
```
## Notes



