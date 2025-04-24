# jlox

A Java-based tree-walking interpreter for the Lox programming language, built by following the book [*Crafting Interpreters*](https://craftinginterpreters.com/) by Bob Nystrom.

## Running the Interpreter
- **Clone the repository**
  ```bash
  git clone https://github.com/your-username/jlox-interpreter.git
  cd jlox-interpreter
  ```
- **Compile the code**
  ```bash
  javac -d bin src/com/craftinginterpreters/lox/*.java
  ```
- **Run the interpreter**
  ```bash
  java -cp bin/ com.craftinginterpreters.lox.Lox [optional file]
  ```

Provide a ```.lox``` file to execute it. Leave it blank to enter **REPL** mode.
