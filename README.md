```cpp
#include <array>
#include <cstdint>
#include <string_view>

enum class State {
    Compiling,
    DebuggingDMA,
    OnTheCourt
};

struct Engineer {
    std::string_view name         = "Colin Sianturi";
    std::string_view university   = "UC Irvine";
    std::string_view degree       = "M.S. Computer Engineering";
    std::uint16_t    graduation   = 2027;
    std::string_view incomingRole = "Software Engineer II @ Raytheon";
    State            status       = State::DebuggingDMA; // usually a missing memory barrier

    std::array<std::string_view, 4> interests = {
        "Systems & Kernel Development",
        "Computer Architecture & Hardware Acceleration",
        "GPU Architecture & Real-Time Graphics",
        "Performance Engineering & Low-Latency Optimization"
    };

    std::array<std::string_view, 3> offClock = {
        "Pickup Basketball (mid-range pull-ups only)",
        "Boxing & Lifting",
        "Competitive FPS / Fighting Games"
    };
};

inline constexpr Engineer colin{};
```
