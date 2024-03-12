# MiniLang Parser

This project focuses on designing and implementing a parser for the MiniLang programming language, emphasizing syntax analysis. MiniLang is a simple language supporting arithmetic operations, variable assignments, if-else conditions, and print statements.

## Language Specifications

The MiniLang parser uses token types identified by the scanner, covering integer and boolean data types, arithmetic and logical operators, keywords, identifiers, literals, and comments. The grammar defines rules for arithmetic expressions, variable assignments, conditional statements (if-else), and print statements.

## Parser Implementation

### Parser Type

This parser is implemented as a **recursive descent parser**, chosen for its simplicity and ease of implementation, suitable for the relatively straightforward syntax of MiniLang.

### Grammar Rules

The parser adheres to the grammar rules of MiniLang, implementing constructs such as expressions, statements, and programs.

### Syntax Tree

The parser constructs an **abstract syntax tree (AST)** representing the hierarchical structure of the MiniLang source code. Each node in the tree corresponds to a language construct.

### Error Handling

The parser includes robust error handling mechanisms, detecting and reporting syntax errors with clear and meaningful messages. It may also provide suggestions for corrections when applicable.

## Documentation

The project documentation encompasses design decisions, the structure of the parser, and instructions on running the program.

### Running the Program

1. Ensure you have Python installed on your system.
2. Save your MiniLang source code in a file (e.g., `example.minilang`).
3. Open a terminal or command prompt.
4. Navigate to the directory containing your parser script.
5. Run the following command:

```bash
python minilang_parser.py path/to/your/source_code.minilang
