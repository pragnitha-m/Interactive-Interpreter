# Interactive Interpreter

## Interactive Interpreter GUI

The Interactive Interpreter GUI is a Python module that provides a graphical user interface (GUI) for an interpreter application. It allows users to input expressions and evaluate them based on specific rules.

### Features

- Input expressions with alphabets (A to E), operators (+, -, *), and numbers (up to two digits).
- Specify operands in expressions.
- Limit one operator per input statement.
- Restrict spaces in input.
- Define valid expressions like 'Alphabet = Number', 'Alphabet = Alphabet', or '(Alphabet/Number) (Operator) (Alphabet/Number)'.
- Stop taking input and get output with the 'RUN' button.
- Clear input for new entries with the 'Clear' button.
- Help menu with detailed instructions.

### Usage

To run the Interpreter GUI, execute `InterpreterGUI.start_window()`. It opens a graphical interface where users can input expressions, run the interpreter, and view the output.

### Help Menu

The 'Help Menu' provides detailed instructions on using the interpreter, ensuring proper expression input.

## Interactive Interpreter Runner

The Interactive Interpreter Runner is a console-based Python module that facilitates running an interpreter through the console. It takes input statements, evaluates expressions, and displays the output.

### Features

- Input statements through the console.
- Evaluate expressions following specific rules.
- Handle alphanumeric characters, operators, and numbers.
- Ensure valid expressions, variables, and operators.
- Display informative messages for invalid inputs.

### Usage

To use the Interactive Interpreter Runner, execute `InterpreterRunner.statement_evaluator()`. It prompts the user to input statements, evaluates them, and displays the output.
