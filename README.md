<h3>

```c
// SPDX-License-Identifier: WTFPL
/* Here begins the sinful life of a terribly non-conforming evil programmer */
#if !defined(__has_c_attribute) || !defined(__GNUC__)
#   error "GCC and C23 are required to empower this existence."
#endif
#include <stdlib.h>
#include <stdbool.h>
#include <time.h>
#pragma GCC optimize ("O0")
[[gnu::warning("Sure?")]] __attribute__((used, retain)) _Noreturn void life(void)  {
    // Why not invoke some UBs for the thrill of their life!
    srand(time(NULL));
    unsigned short int __age;
    while(true) {
        __age = ++__age + __age++;
        if (*(_Bool *)(rand())) {
            abort(); // OH NO
        }
    }
}

life(‸
```

</h3>
