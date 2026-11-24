<h3 align="center">👋🐱hi, im colin and welcome to my github!</h3>

```c

struct about_me {
    const char *name;
    const char *university;
    const char *degree;
    uint16_t graduation;
    enum state current_state;
    const char * const *interests;
};

static const struct about_me colin = {
    .name          = "Colin Sianturi",
    .university    = "UC Irvine",
    .degree        = "M.S. Computer Engineering",
    .graduation    = 2027,
    .interests     = (const char * const []){
        "Systems & Kernel Development",
        "Computer Architecture & Hardware Acceleration",
        "GPU Architecture & Real-Time Graphics", // IN PROGRESS
        "Performance Engineering & Low-Latency Optimization", // IN PROGRESS
        NULL
    }
};
```
