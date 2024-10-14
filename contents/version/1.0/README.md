# Blang Programming Language

Blang is a custom programming language that transpiles to JavaScript. It combines features from Python and JavaScript to create a unique and intuitive syntax.

## Features

- Python-like syntax with JavaScript interoperability
- Custom module system
- String interpolation
- List comprehensions
- Class-based object-oriented programming
- Error handling
- Modern JavaScript features (ternary operator, nullish coalescing)

## Installation

To install Blang, follow these steps:

1. Clone the repository:
   ```
   git clone https://github.com/your-username/blang.git
   cd blang
   ```

2. Install dependencies:
   ```
   npm install
   ```

3. Link the Blang CLI globally:
   ```
   npm link
   ```

## Usage

### Running a Blang File

To run a Blang file, use the following command:

```
blang path/to/your/file.blang
```

### Creating a New Blang Project

To create a new Blang project, use:

```
blang create my-project
cd my-project
```

This will set up a new Blang project with a basic structure.

## Syntax Overview

### Module Import

```javascript
module select math * for mathematical operations
```

### Function Definition

```javascript
func greet(name) {
    print(f"Hello, {name}!")
}
```

### Variables

```javascript
let mutable_var = "I can be changed"
const IMMUTABLE_VAR = "I cannot be changed"
```

### String Interpolation

```javascript
let name = "Blang"
print(f"Welcome to {name}!")
```

### Conditional Statements

```javascript
if condition {
    print("Condition is true")
} else {
    print("Condition is false")
}
```

### Loops

```javascript
loop i in range(5) {
    print(f"Iteration {i}")
}
```

### List Comprehensions

```javascript
let squares = [x * x for x in range(10)]
```

### Error Handling

```javascript
try {
    # Some code that might throw an error
} catch error {
    print(f"An error occurred: {error}")
}
```

### Classes

```javascript
class Animal {
    func constructor(name) {
        this.name = name
    }

    func speak() {
        print(f"{this.name} makes a sound")
    }
}

class Dog extends Animal {
    func speak() {
        print(f"{this.name} barks")
    }
}
```

## Project Structure

- `src/`
  - `core/`: Core transpiler logic
  - `cli/`: Command-line interface
  - `utils/`: Utility functions and error handling
- `examples/`: Example Blang code
- `test/`: Test files

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
