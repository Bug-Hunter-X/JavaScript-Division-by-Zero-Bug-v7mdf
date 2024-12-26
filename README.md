# JavaScript Division by Zero Bug

This repository demonstrates a common JavaScript bug involving division by zero. The original code (`bug.js`) does not handle the case where the denominator is zero, resulting in `Infinity` being returned.  The solution (`bugSolution.js`) addresses this by adding explicit error handling.

## Bug
The function `foo` in `bug.js` does not handle the scenario when `b` is zero.

## Solution
The corrected function in `bugSolution.js` uses a conditional statement to check for division by zero before performing the calculation. If the denominator is zero, an error message is displayed or an alternative value (like NaN) is returned, preventing unexpected behavior or crashes. 
