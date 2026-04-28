1. values added:  20
2. final result:  20
3. You should not use `var`, because `var` has no block scope, which in this case means that `result` is still visible at line 13 even though it was declared inside `if`.
4. values added:  20
5. The code returns an error, because `let result` was used, which means that `result` is only visible inside `if`.
6. The code returns an error, because a constant cannot be reassigned.
7. The code returns an error, because a constant cannot be reassigned.