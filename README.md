# Font Awesome C++ API (`fa_api.h`)

This repository contains a C++ header file (`fa_api.h`) that provides an easy-to-use interface for working with Font Awesome icons in C++ applications. Each Font Awesome icon is mapped to its corresponding Unicode value via macros, allowing developers to reference icons by their names instead of raw Unicode values.

## Features
- **Simplified Usage**: Use meaningful macro names (e.g., `FA_home`, `FA_user`) instead of raw Unicode values.
- **Auto-Generated**: The header file is generated programmatically, ensuring accuracy and ease of updates when new Font Awesome versions are released.
- **Lightweight**: No external dependencies—just include the header file in your project.

## Installation

1. Download the `fa_api.h` file from this repository.
2. Include it in your C++ project:
   ```cpp
   #include "fa_api.h"
   ```
3. Start using the macros in your code:
   ```cpp
   std::cout << "Home Icon: " << SW_home << std::endl;
   ```

## Usage Example

Here’s an example of how to use the `fa_api.h` file in your C++ application:

```cpp
#include <iostream>
#include "fa_api.h"

int main() {
    // Print Font Awesome icons using their macro names
    std::cout << "Smiley Icon: " << SW_smiley << std::endl;
    std::cout << "Home Icon: " << SW_home << std::endl;
    std::cout << "User Icon: " << SW_user << std::endl;

    return 0;
}
```

**Output**:
```
Smiley Icon: 😀
Home Icon: 🏠
User Icon: 👤
```

## Acknowledgments
- [Font Awesome](https://fontawesome.com/) for providing the iconic font and CSS toolkit.
- This project was inspired by the need to simplify the integration of Font Awesome icons into C++ applications as the Font Awesome cheatsheet is not correctly representing the .otf file's unicodes.
