# Test Case Report - Simple Calculator

Columns: ID | Description | Steps | Input | Expected Output | Actual Output | Result | Evidence

TC1 | Basic addition | 1) press 2, +, 3, = | "2+3" | "5" | 5 | Pass | screenshot1.png
TC2 | Basic subtraction | press 9, -, 4, = | "9-4" | "5" | 5 | Pass | screenshot2.png
TC3 | Multiplication | press 6, *, 7, = | "6*7" | "42" | 42 | Pass | screenshot3.png
TC4 | Division | press 8, /, 2, = | "8/2" | "4" | 4 | Pass | screenshot4.png
TC5 | Division by zero | press 8, /, 0, = | "8/0" | "Error: Division by zero" | Error: Division by zero | Pass | screenshot5.png
TC6 | Decimal calculation | press 2, ., 5, +, 1, ., 25, = | "2.5+1.25" | "3.75" | 3.75 | Pass | screenshot6.png
TC7 | Operator precedence | press 2, +, 3, *, 4, = | "2+3*4" | "14" | 14 | Pass | screenshot7.png
TC8 | Backspace | enter 123, Backspace | "12" | 12 displayed in expression | Pass | screenshot8.png
TC9 | Clear | enter 345, C | "" and result 0 | Pass | screenshot9.png
TC10 | Keyboard support | type on keyboard "5*5Enter" | "25" | Pass | screenshot10.png
TC11 | Sequential operations | 5 + 5 = => result 10, then press * 2 = -> 20 | chaining | Pass | screenshot11.png
TC12 | Invalid input prevention (double dot) | press 1 . . 2 | should prevent second dot | Pass | screenshot12.png