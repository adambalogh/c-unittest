# c-unittest
Very basic unit testing library for C.

Example usage:
```

 #include "unittest.h"
 
 #include "socket.h"

 
 static int test_add() {
     mu_assert(1 == 1);
 
     return 0;
 }
 
 static int all_tests() {
     mu_run_test(test_socket_entry_new);
     return 0;
 }
 ```
