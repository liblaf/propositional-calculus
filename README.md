# Propositional Calculus

This is the programming homework of Discrete Mathematics(1).

## Homework 1

### Usage

Run [`converter.py`](https://github.com/godvix/propositional-calculus/blob/master/converter.py) and input an infix expression, the corresponding prefix expression and postfix expression will be displayed in terminal. If an illegal character or a syntax error is detected, an error message will be displayed to indicate where the first error occurs in the expression.

Another simpler version of converter is provided in [`naive_converter.py`](https://github.com/godvix/propositional-calculus/blob/master/naive_converter.py) which does not perform grammar check.

### Implementation

[`converter.py`](https://github.com/godvix/propositional-calculus/blob/master/converter.py) is based on LARA Parser, using transition table generated by [dabeaz/ply: Python Lex-Yacc (github.com)](https://github.com/dabeaz/ply), but does not depend on ply.

[`naive_converter.py`](https://github.com/godvix/propositional-calculus/blob/master/naive_converter.py) is a much simpler version using stack.

## Homework 2

### Usage

Run [`evaluator.py`](https://github.com/godvix/propositional-calculus/blob/master/evaluator.py) and input an infix expression, the truth table and principal disjunctive/conjunctive normal form will be displayed in terminal.

Note that tokens `0`, `F`, `False`, `false` will be interpreted as constant `False`, and `1`, `T`, `True`, `true` will be interpreted as constant `True`.

