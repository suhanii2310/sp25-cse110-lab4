1. values added: 20
2. final result: 20
3. var is function scoped which means even if a variable is declared using var inside an if block or a for loop it can be accesed throughout the whole function. This behavior can result in unexpected bugs if not handles carefully.
4. values added: 20
5. Error. Since the result variable is initialized with "let" its scope is only the if block. Thus accessing it outside the if block is not possible giving an error.
6. Error. Since the result variable is initialized with "const" we cannot reassign it. This results in an error at line 7.
7. Error. Since the result variable is initialized with "const" we cannot reassign it. This results in an error at line 7.