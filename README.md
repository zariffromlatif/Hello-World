# HelloWorld Python Project

## Overview

This is a simple Python project that demonstrates how to use the `ctypes` library to interact with Windows API functions. Specifically, it creates a message box using the `MessageBoxW` function from the `User32.dll` and handles the user's response.

## Features

- Displays a message box with a custom message and caption.
- Handles user responses (e.g., clicking "OK" or "Cancel").
- Includes error handling for potential issues when calling the Windows API.

## Requirements

- Python 3.x
- A Windows operating system (required to use `User32.dll` and `Kernel32.dll`).

## Setup

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/zariffromlatif/HelloWorld-Python.git
   cd HelloWorld-Python
   ```

2. **Run the Script:**

   Make sure you have Python installed. Run the script by navigating to the project directory and executing:

   ```bash
   python HelloWorld.py
   ```

## Usage

When you run the script, a message box will appear with the following details:

- **Message:** "Hello World"
- **Caption:** "Hello Students!"
- **Buttons:** "OK" and "Cancel"

Depending on the user's action, the script will print either "User Clicked Ok!" or "User Clicked Cancel" in the console.

## Error Handling

If there is an issue with calling the Windows API functions, the script will print the error code and exit.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request or open an Issue.

## Contact

For any inquiries or feedback, please reach out to zariffromlatif@gmail.com

---

Feel free to customize the repository link, contact information, or any other details to fit your specific needs.
