1. Line 9 prints 'values added: 20'
2. Line 13 prints 'final result: 20'
3. var declares the variable in function scope which means that it can be accessed out of the block it was declared in. This can lead to naming conflicts and other scoping issues. 
4. Line 9 prints 'values added: 20'
5. Line 13 returns an error as it tries to access result which is out of its scope as it was declared with the 'let' keyword inside the if block. 
6. We don't get to line 9 here as the code returns an error before it. As we try to reassign a value to a 'const' variable in line 7 which is not allowed. 
7. We don't get to line 13 here as the code returns an error before it. As we try to reassign a value to a 'const' variable in line 7 which is not allowed. 