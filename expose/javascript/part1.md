1. line 9 prints 20.
2. line 13 also prints 20.
3. "var" is not block scoped, it is either function scoped or global scoped. This can be a huge problem with naming conflicts and scope issues.
4. line 9 prints 20, just like previously
5. line 13 returns an error, because with the "let" type, the variable is in block scope, and line 13 is outside of the "if" block statement.
6. line 9 prints 0
7. line 13 gives an error, again because "const" is only within the block scope of "if" so it cannot be reached by line 13