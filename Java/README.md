# Expression parser with Exceptions
Implement classes `CheckedAdd`, `CheckedSubtract`, `CheckedMultiply` and `CheckedDivide`. Add to this classes exceptions processing:
- parsing errors;
- evaluation errors.

For expression `1000000*x*x*x*x*x/(x-1)` and for respective value of `x` the results should be:

x | f
--- | ---
0 | 0
1 | division by zero
2 | 32000000
3 | 121500000
4 | 341333333
5 | overflow
6 | overflow
7 | overflow
8 | overflow
9 | overflow
10 | overflow
               