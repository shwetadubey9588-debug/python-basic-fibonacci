# README Audit

## README Fact-Check Table

| Claim Made in README                                               | True?                           | Evidence / Correction Made                                                                                  |
| ------------------------------------------------------------------ | ------------------------------- | ----------------------------------------------------------------------------------------------------------- |
| Program calculates a Fibonacci number                              | Yes                             | The program calculates a value from the Fibonacci sequence.                                                 |
| Program calculates Fibonacci of a user-entered number              | Depends on code                 | This claim is true only if `fibonacci.py` uses `input()`. Otherwise, the claim should be removed.           |
| Program accepts input from the terminal                            | Depends on code                 | This claim is true only if the program contains an `input()` function.                                      |
| Program can calculate Fibonacci for any number entered by the user | Depends on code                 | This is true only if the program accepts user input and calculates the corresponding Fibonacci value.       |
| Program validates negative numbers                                 | No evidence                     | Unless the code contains a condition such as `if n < 0`, this claim should be deleted.                      |
| Program handles invalid input                                      | No evidence                     | Unless the code contains validation or `try/except` handling, this claim should be deleted.                 |
| Python 3 is required                                               | Yes                             | `fibonacci.py` is a Python script and can be run using Python 3.                                            |
| NumPy is required                                                  | No                              | There is no need for NumPy unless `fibonacci.py` explicitly imports and uses it.                            |
| `requirements.txt` is required                                     | No                              | No external dependency file is required for a basic Fibonacci Python program.                               |
| Program can be run using `python fibonacci.py`                     | Yes                             | `fibonacci.py` is a standalone Python script.                                                               |
| Program displays an input prompt                                   | Depends on code                 | This claim should only be included if `fibonacci.py` actually uses `input()` and prints a prompt.           |
| Output is `5` when the input/position is `5`                       | Yes, if using standard indexing | The standard Fibonacci sequence is `0, 1, 1, 2, 3, 5`, so the Fibonacci value at position `5` is `5`.       |
| Program uses a loop                                                | Depends on code                 | This claim is true only if the Fibonacci calculation is implemented using a `for` or `while` loop.          |
| Program uses addition to calculate Fibonacci numbers               | Yes, if iterative               | Fibonacci values are calculated by adding the two preceding values in an iterative implementation.          |
| Program uses two previous values to calculate the next value       | Yes, if iterative               | The next Fibonacci value is obtained by adding the previous two values.                                     |
| Initial Fibonacci values are `0` and `1`                           | Yes                             | The standard Fibonacci sequence begins with `0` and `1`.                                                    |
| Program has input validation                                       | No evidence                     | No validation should be claimed unless validation logic is present in the code.                             |
| Program has error handling                                         | No evidence                     | No error handling should be claimed unless `try`, `except`, or equivalent logic exists.                     |
| Program uses external Python libraries                             | No                              | A basic Fibonacci calculator can be implemented using only Python's built-in features.                      |
| Project uses MIT License                                           | No evidence                     | A license should only be claimed if a `LICENSE` file exists in the repository.                              |
| `pip install -r requirements.txt` is a valid installation step     | No                              | No external packages are required for a basic Fibonacci calculator, so this command should not be included. |
| Project contains a Fibonacci calculator                            | Yes                             | `fibonacci.py` contains the program for calculating a Fibonacci number.                                     |
