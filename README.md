# c-unittest
Very basic unit testing library for C.

Example usage:
```c

 #include "unittest.h"
 
 #include "socket.h"

 
 static int test_add() {
     mu_assert(1 == 1);
 
     return 0;
 }
 
 static int all_tests() {
     mu_run_test(test_add);
     return 0;
 }
 ```
