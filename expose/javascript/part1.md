1. Line 9 prints values added:  20
2. Line 13 prints final result:  20
3. We shouldn't use var because we can access variables with var type beyond the scope of   the block it belongs to, which can cause data leak. We are also able to redeclare the variable of var type, which can be problematic.
4. Line 9 prints values added: 20
5. Line 13 returns an error because variable of let type cannot be accessed in a block that is out of the scope of the let variable
6. Line 9 returns an error because variable of const type cannot be reassigned
7. Line 13 returns an error because variable of const type cannot be accessed in a block out of the scope of the const variable