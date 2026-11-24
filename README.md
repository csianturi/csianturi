<h3 align="center">👋😺hi, i'm colin welcome to my github!</h3>

```#include <stdint.h>

enum state {
    STATE_EAT,
    STATE_DOOMSCROLL,
    STATE_LARP
};

struct soon_to_be_engineer {
    const char *name;
    const char *university;
    const char *degree;
    uint16_t graduation;
    enum state current_state;
    const char * const *interests;
    const char * const *off_clock;
};

static const struct engineer colin = {
    .name          = "Colin Sianturi",
    .university    = "UC Irvine",
    .degree        = "M.S. Computer Engineering",
    .graduation    = 2027,
    .current_state = STATE_LARP
    .interests     = (const char * const []){
        "Systems & Kernel Development",
        "Computer Architecture & Hardware Acceleration",
        "GPU Architecture & Real-Time Graphics", // IN PROGRESS
        "Performance Engineering & Low-Latency Optimization", // IN PROGRESS
        NULL
    }
};
```
