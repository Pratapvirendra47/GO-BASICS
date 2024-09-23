# GO-BASICS
The repo includes basics of go


src : `https://github.com/firtman/go-fundamentals`
## GO RULES

- Every file in go must with in the package.
- For every GO solution we are creating will have entry point starting with main
- when you deploy go application you dont deploy the source code you deploy the binary that you need to compile.

- Go can handle Source code , Byte Code and machine code
- Go is faster than Python.
- GO is written in machine language i.e. can be directly run by CPU. It is binary format that doesn't require any complier.
- Go is statically typed while Python is dynamically typed.
- Not an Object Oriented language. No try catch or exception. We have design pattern to work with errors.
- A module is a group of packages.

- creating a module : go init mod <module name>
- go.mod us kind of package.json.
	- it lists all the dependencies.
- go workspace can have multiple modules.

## const vs immutable variable

- immutable variable is a variable that is space in memory. Address that it has been allocated.
- immutable variable can be set after the compilation where as constants is set at the start of the compilation. A constant cannot set its value in runtime.