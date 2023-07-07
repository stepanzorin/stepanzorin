## [![Telegram](https://img.shields.io/badge/-contact_me_via_Telegram-090909?style=for-the-badge&logo=telegram&logoColor=27A0D9)](https://t.me/zorinsa)

```cpp
#include <array>
#include <cstdlib>
#include <string_view>

#include <fmt/core.h>

namespace github::stepanzorin {

struct SoftwareEngineer final {
    const std::string_view name{"Stepan Zorin"};
    const std::uint8_t age{24};
    const bool is_male{true};
    const std::string_view country{"Russia"};

    static const std::size_t count_of_language_spoken{2};
    const std::array<std::string_view, count_of_language_spoken> language_spoken{"Russian (native speaker)",
                                                                                 "United States english"};

    void say_hi() const noexcept { fmt::print("Thanks for dropping by, hope you find some of my work interesting."); }
};

}

using namespace github::stepanzorin;

int main() {
    constexpr SoftwareEngineer me;
    me.say_hi();

    return EXIT_SUCCESS;
}
```

### 🔧 Technologies & Tools
![C++](https://img.shields.io/badge/-C++-090909?style=for-the-badge&logo=C%2b%2b&logoColor=6296CC)
![Vulkan API](https://img.shields.io/badge/-vulkan-090909?style=for-the-badge&logo=vulkan&logoColor=ae0e28)
![CLion](https://img.shields.io/badge/-CLion-090909?style=for-the-badge&logo=CLion&logoColor=FFFFFF)
![CMake](https://img.shields.io/badge/-CMake-090909?style=for-the-badge&logo=CMake&logoColor=6296CC)
![Conan](https://img.shields.io/badge/-Conan-090909?style=for-the-badge&logo=Conan&logoColor=6296CC)
![Windows](https://img.shields.io/badge/-Windows-090909?style=for-the-badge&logo=Windows&logoColor=6296CC)
![MacOS](https://img.shields.io/badge/-MacOS-090909?style=for-the-badge&logo=MacOS&logoColor=6296CC)
