# data-structure

# Data structure transformation for programming practices and algorithms

## All data types from Go, Python, Kotlin, Java, TypeScript, C++, Rust, C#
- [ ] [Go](#go)
- [ ] [Python](#python)
- [ ] [Kotlin](#kotlin)
- [ ] [Java](#java)
- [ ] [TypeScript](#typescript)
- [ ] [C++](#c++)
- [ ] [Rust](#rust)
- [ ] [C#](#c#)



## Go
- [ ] int, int8, int16, int32, int64
	- int: `var val int = 10`
	- int8: `var val int8 = 10`
	- int16: `var val int16 = 10`
	- int32: `var val int32 = 10`
	- int64: `var val int64 = 10`
- [ ] uint, uint8, uint16, uint32, uint64, uintptr
	- uint: `var val uint = 10`
	- uint8: `var val uint8 = 10`
	- uint16: `var val uint16 = 10`
	- uint32: `var val uint32 = 10`
	- uint64: `var val uint64 = 10`
	- uintptr: `var val uintptr = 10`
- [ ] float32, float64
  - float32: `var val float32 = 10.0`
	- float64: `var val float64 = 10.0`
- [ ] complex64, complex128
  - complex64: `var val complex64 = 10.0`
	- complex128: `var val complex128 = 10.0`
- [ ] byte, rune
  - byte: `var val byte = 10`
	- rune: `var val rune = 10`
- [ ] bool
	- bool: `var val bool = true`
- [ ] string
	- string: `var val string = "Hello World"`
- [ ] array
	- array: `var val [5]int = [5]int{1, 2, 3, 4, 5}`
- [ ] slice
	- - slice: `var val [ ]int = [ ]int{1, 2, 3, 4, 5}`
- [ ] map
	- map: `var val map[string]int = map[string]int{"a": 1, "b": 2, "c": 3}`
- [ ] struct
	- struct: `type Person struct { name string }`
- [ ] interface
	- interface: `type Person interface { getName() string }`
- [ ] pointer
	- pointer: `var val *int = &val`
- [ ] function
	- function: `func add(a int, b int) int { return a + b }`
- [ ] channel
	- channel: `var val chan int = make(chan int)`

## Python
- [ ] int, float, complex
  - int: `val = 10`
	- float: `val = 10.0`
	- complex: `val = 10.0`
- [ ] bool
	- bool: `val = True`
- [ ] str
	- str: `val = "Hello World"`
- [ ] list
	- list: `val = [1, 2, 3, 4, 5]`
- [ ] tuple
	- tuple: `val = (1, 2, 3, 4, 5)`
- [ ] set
	- set: `val = {1, 2, 3, 4, 5}`
- [ ] dict
	- dict: `val = {"a": 1, "b": 2, "c": 3}`
- [ ] function
	- function: `def add(a, b): return a + b`
- [ ] class
	- class: `class Person: def __init__(self, name): self.name = name`
- [ ] module
	- module: `import math`
- [ ] None
	- None: `val = None`

## Kotlin
- [ ] Byte, Short, Int, Long
	- Byte: `val val: Byte = 10`
	- Short: `val val: Short = 10`
	- Int: `val val: Int = 10`
	- Long: `val val: Long = 10`
- [ ] Float, Double
	- Float: `val val: Float = 10.0`
	- Double: `val val: Double = 10.0`
- [ ] Char
	- Char: `val val: Char = 'a'`
- [ ] Boolean
	- Boolean: `val val: Boolean = true`
- [ ] String
	- String: `val val: String = "Hello World"`
- [ ] Array
	- Array: `val val: Array<Int> = arrayOf(1, 2, 3, 4, 5)`
- [ ] List
	- List: `val val: List<Int> = listOf(1, 2, 3, 4, 5)`
- [ ] Set
	- Set: `val val: Set<Int> = setOf(1, 2, 3, 4, 5)`
- [ ] Map
	- Map: `val val: Map<String, Int> = mapOf("a" to 1, "b" to 2, "c" to 3)`
- [ ] Function
	- Function: `fun add(a: Int, b: Int): Int = a + b`
- [ ] Class
	- Class: `class Person(val name: String)`
- [ ] Interface
	- Interface: `interface Person { fun getName(): String }`
- [ ] Object
	- Object: `object Person { fun getName(): String = "Hello World" }`
- [ ] Enum
	- Enum: `enum class Person { A, B, C }`
- [ ] Sealed class
	- Sealed class: `sealed class Person { class A: Person() class B: Person() class C: Person() }`
- [ ] Type alias
	- Type alias: `typealias Person = String`
- [ ] Nullable
	- Nullable: `val val: Int? = null`
- [ ] Nothing
	- Nothing: `val val: Nothing = throw Exception()`
- [ ] Unit
	- Unit: `val val: Unit = Unit`
- [ ] Any
	- Any: `val val: Any = 10`

## Java
- [ ] byte, short, int, long
	- byte: `byte val = 10`
	- short: `short val = 10`
	- int: `int val = 10`
	- long: `long val = 10`
- [ ] float, double
	- float: `float val = 10.0`
	- double: `double val = 10.0`
- [ ] char
	- char: `char val = 'a'`
- [ ] boolean
	- boolean: `boolean val = true`
- [ ] String
	- String: `String val = "Hello World"`
- [ ] array
	- - array: `int[ ] val = new int[ ]{1, 2, 3, 4, 5}`
- [ ] List
	- List: `List<Integer> val = Arrays.asList(1, 2, 3, 4, 5)`
- [ ] Set
	- Set: `Set<Integer> val = new HashSet<>(Arrays.asList(1, 2, 3, 4, 5))`
- [ ] Map
	- Map: `Map<String, Integer> val = new HashMap<>(); val.put("a", 1); val.put("b", 2); val.put("c", 3)`
- [ ] Function
	- Function: `int add(int a, int b) { return a + b; }`
- [ ] Class
	- Class: `class Person { String name; Person(String name) { this.name = name; } }`
- [ ] Interface
	- Interface: `interface Person { String getName(); }`
- [ ] Enum
	- Enum: `enum Person { A, B, C }`
- [ ] Nullable
	- Nullable: `Integer val = null`
- [ ] Void
	- Void: `void val = null`
- [ ] Object
	- Object: `Object val = new Object()`
- [ ] Any
	- Any: `Object val = new Object()`

## TypeScript
- [ ] number
	- number: `let val: number = 10`
- [ ] boolean
	- boolean: `let val: boolean = true`
- [ ] string
	- string: `let val: string = "Hello World"`
- [ ] array
	- - array: `let val: number[ ] = [1, 2, 3, 4, 5]`
- [ ] tuple
	- tuple: `let val: [number, string] = [1, "Hello World"]`
- [ ] enum
	- enum: `enum Person { A, B, C }`
- [ ] any
	- any: `let val: any = 10`
- [ ] void
	- void: `let val: void = undefined`
- [ ] null
	- null: `let val: null = null`
- [ ] undefined
	- undefined: `let val: undefined = undefined`
- [ ] never
	- never: `let val: never = throw new Error()`
- [ ] object
	- object: `let val: object = { a: 1, b: 2, c: 3 }`
- [ ] unknown
	- unknown: `let val: unknown = 10`
- [ ] function
	- function: `function add(a: number, b: number): number { return a + b }`
- [ ] class
	- class: `class Person { constructor(public name: string) {} }`
- [ ] interface
	- interface: `interface Person { getName(): string }`
- [ ] type alias
	- type alias: `type Person = string`
- [ ] union
	- union: `let val: number | string = 10`
- [ ] intersection
	- intersection: `let val: number & string = 10`
- [ ] literal
	- literal: `let val: 1 | 2 | 3 = 1`
- [ ] type guard
	- type guard: `if (typeof val === "number") { console.log(val) }`
- [ ] type assertion
	- type assertion: `let val: unknown = 10; (val as number).toFixed(2)`
- [ ] generics
	- generics: `function add<T>(a: T, b: T): T { return a + b }`
- [ ] decorators
	- decorators: `@Component() class Person

## C++
- [ ] int, short, long, long long
	- int: `int val = 10`
	- short: `short val = 10`
	- long: `long val = 10`
	- long long: `long long val = 10`
- [ ] float, double
	- float: `float val = 10.0`
	- double: `double val = 10.0`
- [ ] char
	- char: `char val = 'a'`
- [ ] bool
	- bool: `bool val = true`
- [ ] string
	- string: `string val = "Hello World"`
- [ ] array
	- array: `int val[5] = {1, 2, 3, 4, 5}`
- [ ] vector
	- vector: `vector<int> val = {1, 2, 3, 4, 5}`
- [ ] map
	- map: `map<string, int> val = {{"a", 1}, {"b", 2}, {"c", 3}}`
- [ ] function
	- function: `int add(int a, int b) { return a + b; }`
- [ ] class
	- class: `class Person { string name; Person(string name) { this.name = name; } }`
- [ ] interface
	- interface: `class Person { virtual string getName() = 0; }; class A: Person { string getName() override { return "A"; } }; class B: Person { string getName() override { return "B"; } }; class C: Person { string getName() override { return "C"; } };`
- [ ] enum
	- enum: `enum Person { A, B, C };`
- [ ] union
	- union: `union Person { int a; float b; };`
- [ ] struct
	- struct: `struct Person { string name; };`
- [ ] pointer
	- pointer: `int val = 10; int *ptr = &val;`
- [ ] reference
	- reference: `int val = 10; int &ref = val;`
- [ ] template
	- template: `template <typename T> T add(T a, T b) { return a + b; }`
- [ ] namespace
	- namespace: `namespace Person { string getName()	{ return "Hello World"; } }`
- [ ] nullptr
	- nullptr: `int *ptr = nullptr;`
- [ ] void
	- void: `void val = nullptr;`

## Rust
- [ ] i8, i16, i32, i64, i128, isize
	- i8: `let val: i8 = 10`
	- i16: `let val: i16 = 10`
	- i32: `let val: i32 = 10`
	- i64: `let val: i64 = 10`
	- i128: `let val: i128 = 10`
	- isize: `let val: isize = 10`
- [ ] u8, u16, u32, u64, u128, usize
	- u8: `let val: u8 = 10`
	- u16: `let val: u16 = 10`
	- u32: `let val: u32 = 10`
	- u64: `let val: u64 = 10`
	- u128: `let val: u128 = 10`
	- usize: `let val: usize = 10`
- [ ] f32, f64
	- f32: `let val: f32 = 10.0`
	- f64: `let val: f64 = 10.0`
- [ ] char
	- char: `let val: char = 'a'`
- [ ] bool
	- bool: `let val: bool = true`
- [ ] str
	- str: `let val: &str = "Hello World"`
- [ ] array
	- array: `let val: [i32; 5] = [1, 2, 3, 4, 5]`
- [ ] slice
	- slice: `let val: &[i32] = &[1, 2, 3, 4, 5]`
- [ ] tuple
	- tuple: `let val: (i32, &str) = (1, "Hello World")`
- [ ] enum
	- enum: `enum Person { A, B, C }`
- [ ] struct
	- struct: `struct Person { name: String }`
- [ ] union
	- union: `union Person { a: i32, b: f32 }`
- [ ] function
	- function: `fn add(a: i32, b: i32) -> i32 { a + b }`
- [ ] closure
	- closure: `let add = |a: i32, b: i32| -> i32 { a + b };`
- [ ] trait
	- trait: `trait Person { fn get_name(&self) -> &str; }`
- [ ] impl
	- impl: `impl Person for Person { fn get_name(&self) -> &str { "Hello World" } }`
- [ ] module
	- module: `mod person { pub fn get_name() -> &str { "Hello World" } }`
- [ ] type alias
	- type alias: `type Person = String`
- [ ] generics
	- generics: `fn add<T>(a: T, b: T) -> T { a + b }`
- [ ] lifetime
	- lifetime: `fn add<'a>(a: &'a i32, b: &'a i32) -> &'a i32 { a + b }`

## C#
- [ ] sbyte, short, int, long
	- sbyte: `sbyte val = 10`
	- short: `short val = 10`
	- int: `int val = 10`
	- long: `long val = 10`
- [ ] float, double
	- float: `float val = 10.0`
	- double: `double val = 10.0`
- [ ] char
	- char: `char val = 'a'`
- [ ] bool
	- bool: `bool val = true`
- [ ] string
	- string: `string val = "Hello World"`
- [ ] array
	- - array: `int[ ] val = new int[ ]{1, 2, 3, 4, 5}`
- [ ] list
	- list: `List<int> val = new List<int>{1, 2, 3, 4, 5}`
- [ ] dictionary
	- dictionary: `Dictionary<string, int> val = new Dictionary<string, int>{{"a", 1}, {"b", 2}, {"c", 3}}`
- [ ] function
	- function: `int add(int a, int b) { return a + b; }`
- [ ] class
	- class: `class Person { string name; Person(string name) { this.name = name; } }`
- [ ] interface
	- interface: `interface Person { string getName(); }`
- [ ] enum
	- enum: `enum Person { A, B, C }`
- [ ] struct
	- struct: `struct Person { string name; }`
- [ ] pointer
	- pointer: `int val = 10; int *ptr = &val;`
- [ ] reference
	- reference: `int val = 10; int &ref = val;`
- [ ] delegate
	- delegate: `delegate int Add(int a, int b);`
- [ ] event
	- event: `class Person { public event EventHandler NameChanged; }`
- [ ] namespace
	- namespace: `namespace Person { string getName() { return "Hello World"; } }`
- [ ] null
	- null: `int? val = null;`
- [ ] void
	- void: `void val = null;`
- [ ] object
	- object: `object val = new object();`



# All languages there are the similar data type, may be different name, but the same meaning. below is a group the summary of all data types from all languages that have same meaning.
list of categories:
- [Number](#number)
- [String](#string)
- [Boolean](#boolean)
- [Array](#array)
- [List](#list)
- [Set](#set)
- [Map](#map)
- [Function](#function)
- [Class](#class)
- [Interface](#interface)
- [Enum](#enum)
- [Nullable](#nullable)
- [Void](#void)
- [Object](#object)
- [Any](#any)
- [Pointer](#pointer)

## Number
- Go: int, int8, int16, int32, int64, uint, uint8, uint16, uint32, uint64, uintptr, float32, float64, complex64, complex128
- Python: int, float, complex
- Kotlin: Byte, Short, Int, Long, Float, Double
- Java: byte, short, int, long, float, double
- TypeScript: number
- C++: int, short, long, long long, float, double
- Rust: i8, i16, i32, i64, i128, isize, u8, u16, u32, u64, u128, usize, f32, f64
- C#: sbyte, short, int, long, float, double

## String
- Go: string
- Python: str
- Kotlin: String
- Java: String
- TypeScript: string
- C++: string
- Rust: str
- C#: string

## Boolean
- Go: bool
- Python: bool
- Kotlin: Boolean
- Java: boolean
- TypeScript: boolean
- C++: bool
- Rust: bool
- C#: bool

## Array
- Go: array
- Python: list
- Kotlin: Array
- Java: array
- TypeScript: array
- C++: array
- Rust: array
- C#: array

## List
- Go: slice
- Python: list
- Kotlin: List
- Java: List
- TypeScript: array
- C++: vector
- Rust: slice
- C#: List

## Set
- Go: nil
- Python: set
- Kotlin: Set
- Java: Set
- TypeScript: nil
- C++: set
- Rust: nil
- C#: nil

## Map
- Go: map
- Python: dict
- Kotlin: Map
- Java: Map
- TypeScript: object
- C++: map
- Rust: nil
- C#: dictionary

## Function
- Go: function
- Python: function
- Kotlin: Function
- Java: function
- TypeScript: function
- C++: function
- Rust: function
- C#: function

## Class
- Go: struct
- Python: class
- Kotlin: Class
- Java: class
- TypeScript: class
- C++: class
- Rust: struct
- C#: class

## Interface
- Go: interface
- Python: class
- Kotlin: Interface
- Java: interface
- TypeScript: interface
- C++: interface
- Rust: trait
- C#: interface

## Enum
- Go: nil
- Python: enum
- Kotlin: Enum
- Java: enum
- TypeScript: enum
- C++: enum
- Rust: enum
- C#: enum

## Nullable
- Go: nil
- Python: None
- Kotlin: Nullable
- Java: null
- TypeScript: null
- C++: nullptr
- Rust: nil
- C#: null

## Void
- Go: nil
- Python: nil
- Kotlin: Unit
- Java: void
- TypeScript: void
- C++: void
- Rust: nil
- C#: void

## Object
- Go: nil
- Python: object
- Kotlin: Object
- Java: Object
- TypeScript: object
- C++: nil
- Rust: nil
- C#: object

## Any
- Go: interface{}, any
- Python: any
- Kotlin: Any
- Java: Object
- TypeScript: any
- C++: nil
- Rust: nil
- C#: object

## Pointer
- Go: pointer
- Python: nil
- Kotlin: nil
- Java: nil
- TypeScript: nil
- C++: pointer
- Rust: nil
- C#: nil


# Combination mapping of all types like pair of type to type such as int to int, int to string, string to int, string to string, etc.
list of categories:
- [ ] int to int
	e.g. Go: int to int, Python: int to int, Kotlin: Int to Int, Java: int to int, TypeScript: number to number, C++: int to int, Rust: i32 to i32, C#: int to int
	code example function name that use in real world:
	- [ ] add
		- Go: `func add(a int, b int) int { return a + b }`
		- Python: `def add(a: int, b: int) -> int: return a + b`
		- Kotlin: `fun add(a: Int, b: Int): Int = a + b`
		- Java: `int add(int a, int b) { return a + b; }`
		- TypeScript: `function add(a: number, b: number): number { return a + b }`
		- C++: `int add(int a, int b) { return a + b; }`
		- Rust: `fn add(a: i32, b: i32) -> i32 { a + b }`
		- C#: `int add(int a, int b) { return a + b; }`
	- [ ] subtract
	- [ ] multiply
	- [ ] divide
	- [ ] modulo
	- [ ] power
	- [ ] root
	- [ ] log
	- [ ] factorial
	- [ ] permutation
	- [ ] combination
	- [ ] gcd
	- [ ] lcm
	- [ ] min
	- [ ] max
	- [ ] sum
- [ ] int to string
	e.g. Go: int to string, Python: int to str, Kotlin: Int to String, Java: int to String, TypeScript: number to string, C++: int to string, Rust: i32 to str, C#: int to string
	code example function name that use in real world:
	- [ ] toString
		- Go: `func toString(val int) string { return strconv.Itoa(val) }`
			example: input: 123, output: "123"
		- Python: `def toString(val: int) -> str: return str(val)`
			example: input: 123, output: "123"
		- Kotlin: `fun toString(val: Int): String = val.toString()`
			example: input: 123, output: "123"
		- Java: `String toString(int val) { return Integer.toString(val); }`
			example: input: 123, output: "123"
		- TypeScript: `function toString(val: number): string { return val.toString() }`
			example: input: 123, output: "123"
		- C++: `string toString(int val) { return to_string(val); }`
			example: input: 123, output: "123"
		- Rust: `fn toString(val: i32) -> String { val.to_string() }`
			example: input: 123, output: "123"
		- C#: `string toString(int val) { return val.ToString(); }`
			example: input: 123, output: "123"

	- [ ] toBinary
	- [ ] toOctal
	- [ ] toHex
	- [ ] toRoman
	- [ ] toEnglish (e.g. 1 to one, 2 to two, 3 to three, etc.)
	- [ ] toThaiTextNumber (e.g. 123 to หนึ่งร้อยยี่สิบสาม, 456 to สี่ร้อยห้าสิบหก, etc.)
		- Go: `func toThaiTextNumber(val int) string { return "" }`
			example: input: 123, output: "หนึ่งร้อยยี่สิบสาม"
		- Python: `def toThaiTextNumber(val: int) -> str: return ""`
		- Kotlin: `fun toThaiTextNumber(val: Int): String = ""`
		- Java: `String toThaiTextNumber(int val) { return ""; }`
		- TypeScript: `function toThaiTextNumber(val: number): string { return "" }`
		- C++: `string toThaiTextNumber(int val) { return ""; }`
		- Rust: `fn toThaiTextNumber(val: i32) -> String { "".to_string() }`
		- C#: `string toThaiTextNumber(int val) { return ""; }`

- [ ] string to int
	e.g. Go: string to int, Python: str to int, Kotlin: String to Int, Java: String to int, TypeScript: string to number, C++: string to int, Rust: str to i32, C#: string to int
	code example function name that use in real world:
	- [ ] parseInt
		- Go: `func parseInt(val string) int { return strconv.Atoi(val) }`
			example: input: "2557", output: 2557
		- Python: `def parseInt(val: str) -> int: return int(val)`
			example: input: "2557", output: 2557
		- Kotlin: `fun parseInt(val: String): Int = val.toInt()`
			example: input: "2557", output: 2557
		- Java: `int parseInt(String val) { return Integer.parseInt(val); }`
		- TypeScript: `function parseInt(val: string): number { return parseInt(val) }`
		- C++: `int parseInt(string val) { return stoi(val); }`
		- Rust: `fn parseInt(val: &str) -> i32 { val.parse::<i32>().unwrap() }`
		- C#: `int parseInt(string val) { return int.Parse(val); }`
	- [ ] parseBinary
	- [ ] parseOctal
	- [ ] parseHex
	- [ ] parseRoman
	- [ ] parseEnglish (e.g. one to 1, two to 2, three to 3, etc.)
	- [ ] parseThaiTextNumber (e.g. หนึ่งร้อยยี่สิบสาม to 123, สี่ร้อยห้าสิบหก to 456, etc.)
		- Go: `func parseThaiTextNumber(val string) int { return 0 }`
			example: input: "หนึ่งร้อยยี่สิบสาม", output: 123
		- Python: `def parseThaiTextNumber(val: str) -> int: return 0`
		- Kotlin: `fun parseThaiTextNumber(val: String): Int = 0`
		- Java: `int parseThaiTextNumber(String val) { return 0; }`
		- TypeScript: `function parseThaiTextNumber(val: string): number { return 0 }`
		- C++: `int parseThaiTextNumber(string val) { return 0; }`
		- Rust: `fn parseThaiTextNumber(val: &str) -> i32 { 0 }`
		- C#: `int parseThaiTextNumber(string val) { return 0; }`
- [ ] string to string
	e.g. Go: string to string, Python: str to str, Kotlin: String to String, Java: String to String, TypeScript: string to string, C++: string to string, Rust: str to str, C#: string to string
	code example function name that use in real world in financial domain:
	- [ ] formatNumber
		- Go: `func formatCurrency(val string) string { return "" }`
			example: input: "123456789", output: "123,456,789.00"
		- Python: `def formatCurrency(val: str) -> str: return ""`
		- Kotlin: `fun formatCurrency(val: String): String = ""`
		- Java: `String formatCurrency(String val) { return ""; }`
		- TypeScript: `function formatCurrency(val: string): string { return "" }`
		- C++: `string formatCurrency(string val) { return ""; }`
		- Rust: `fn formatCurrency(val: &str) -> String { "".to_string() }`
			example: input: "123456789", output: "123,456,789.00"
		- C#: `string formatCurrency(string val) { return ""; }`

- [ ] int to float
	e.g. Go: int to float, Python: int to float, Kotlin: Int to Float, Java: int to float, TypeScript: number to number, C++: int to float, Rust: i32 to f32, C#: int to float
	code example function name that use in real world in hospital domain:
	- [ ] calculateBMI
		- Go: `func calculateBMI(weight int, height int) float32 { return 0 }`
			example: input: weight: 60, height: 170, output: 20.76
		- Python: `def calculateBMI(weight: int, height: int) -> float: return 0`
		- Kotlin: `fun calculateBMI(weight: Int, height: Int): Float = 0`
		- Java: `float calculateBMI(int weight, int height) { return 0; }`
		- TypeScript: `function calculateBMI(weight: number, height: number): number { return 0 }`
		- C++: `float calculateBMI(int weight, int height) { return 0; }`
		- Rust: `fn calculateBMI(weight: i32, height: i32) -> f32 { 0.0 }`
			example: input: weight: 60, height: 170, output: 20.76
		- C#: `float calculateBMI(int weight, int height) { return 0; }`

- [ ] int to double
	e.g. Go: int to double, Python: int to float, Kotlin: Int to Double, Java: int to double, TypeScript: number to number, C++: int to double, Rust: i32 to f64, C#: int to double
	code example function name that use in real world in loan domain:
	- [ ] calculateInterest
		- Go: `func calculateInterest(principal int, rate int, year int) float64 { return 0 }`
			example: input: principal: 100000, rate: 5, year: 5, output: 127628.156250
			formula for calculate interest: `A = P(1 + rt)`
			- A = the future value of the investment/loan, including interest
			- P = the principal investment amount (the initial deposit or loan amount)
			- r = the annual interest rate (decimal)
			- t = the time the money is invested or borrowed for (in years)
		- Python: `def calculateInterest(principal: int, rate: int, year: int) -> float: return 0`
		- Kotlin: `fun calculateInterest(principal: Int, rate: Int, year: Int): Double = 0`
		- Java: `double calculateInterest(int principal, int rate, int year) { return 0; }`
		- TypeScript: `function calculateInterest(principal: number, rate: number, year: number): number { return 0 }`
		- C++: `double calculateInterest(int principal, int rate, int year) { return 0; }`
		- Rust: `fn calculateInterest(principal: i32, rate: i32, year: i32) -> f64 { 0.0 }`
			example: input: principal: 100000, rate: 5, year: 5, output: 127628.156250
		- C#: `double calculateInterest(int principal, int rate, int year) { return 0; }`

- [ ] float to int
	e.g. Go: float to int, Python: float to int, Kotlin: Float to Int, Java: float to int, TypeScript: number to number, C++: float to int, Rust: f32 to i32, C#: float to int
	code example function name that use in real world in split the real item to each person:
	- [ ] splitItem
		- Go: `func splitItem(total float32, person int) int { return 0 }`
			example: input: total: 100, person: 3, output: 33
		- Python: `def splitItem(total: float, person: int) -> int: return 0`
		- Kotlin: `fun splitItem(total: Float, person: Int): Int = 0`
		- Java: `int splitItem(float total, int person) { return 0; }`
		- TypeScript: `function splitItem(total: number, person: number): number { return 0 }`
		- C++: `int splitItem(float total, int person) { return 0; }`
		- Rust: `fn splitItem(total: f32, person: i32) -> i32 { 0 }`
			example: input: total: 100, person: 3, output: 33
		- C#: `int splitItem(float total, int person) { return 0; }`

- [ ] float to float
	e.g. Go: float to float, Python: float to float, Kotlin: Float to Float, Java: float to float, TypeScript: number to number, C++: float to float, Rust: f32 to f32, C#: float to float
	code example function name that use in real world in split bill:
	- [ ] splitBill
		- Go: `func splitBill(total float32, person int) float32 { return 0 }`
			example: input: total: 100, person: 3, output: 33.33
		- Python: `def splitBill(total: float, person: int) -> float: return 0`
		- Kotlin: `fun splitBill(total: Float, person: Int): Float = 0`
		- Java: `float splitBill(float total, int person) { return 0; }`
		- TypeScript: `function splitBill(total: number, person: number): number { return 0 }`
		- C++: `float splitBill(float total, int person) { return 0; }`
		- Rust: `fn splitBill(total: f32, person: i32) -> f32 { 0.0 }`
			example: input: total: 100, person: 3, output: 33.33
		- C#: `float splitBill(float total, int person) { return 0; }`

- [ ] float to double
	e.g. Go: float to double, Python: float to float, Kotlin: Float to Double, Java: float to double, TypeScript: number to number, C++: float to double, Rust: f32 to f64, C#: float to double
	code example function name that use in real world in Exchange rate from USD to EUR as a float and amount in USD:
	- [ ] exchangeRate float -> float -> double
		- Go: `func exchangeRate(amount float32, rate float32) float64 { return 0 }`
			example: input: amount: 100, rate: 0.84, output: 84.0
		- Python: `def exchangeRate(amount: float, rate: float) -> float: return 0`
		- Kotlin: `fun exchangeRate(amount: Float, rate: Float): Double = 0`
		- Java: `double exchangeRate(float amount, float rate) { return 0; }`
		- TypeScript: `function exchangeRate(amount: number, rate: number): number { return 0 }`
		- C++: `double exchangeRate(float amount, float rate) { return 0; }`
		- Rust: `fn exchangeRate(amount: f32, rate: f32) -> f64 { 0.0 }`
			example: input: amount: 100, rate: 0.84, output: 84.0
		- C#: `double exchangeRate(float amount, float rate) { return 0; }`

- [ ] double to int
- [ ] double to float
- [ ] double to double
- [ ] int to bool
- [ ] bool to int
- [ ] string to bool
- [ ] bool to string
- [ ] int to array
- [ ] int to list
- [ ] int to set
- [ ] int to map