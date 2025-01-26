# KatoolinV3

KatoolinV3 is a modernized version of the original Katoolin by LionSec, designed to install and manage Kali Linux tools on a Debian-based system. This updated version ensures compatibility with Python 3, offering an improved user interface, expanded tool categories, and better error handling. It provides an easy way to add the Kali Linux repository and install tools categorized by their use cases. Additionally, this version replaces outdated dependencies (e.g., `python-distorm3` with `python3-distorm3`) and features enhanced repository management.

## Features
- Install tools by category (e.g., Information Gathering, Vulnerability Analysis, Wireless Attacks, etc.)
- Search for tools across categories
- Install all tools in a specific category
- Add or remove Kali Linux repositories
- Lightweight and easy to use

## Requirements
- A Debian-based Linux system (e.g., Ubuntu or Debian)
- Python 3.6+ installed

## Installation
1. Clone the repository:
   git clone https://github.com/bisesdulal16/KatoolinV3.git
   cd KatoolinV3
2. Run the script:
   python3 katoolinv3.py
4. Ensure you have root privileges:
   sudo python3 katoolinv3.py

## Usage

### Main Menu Options
- **View Categories**: Displays available tool categories.
- **Update Katoolin**: Updates the tool from the repository.
- **Help**: Displays the list of available commands.
- **Exit**: Exits the tool.

### Commands
- `load=<category>`: Load a specific category to view and install tools.
- `search=<tool>`: Search for a specific tool across all categories.
- `99`: Install all tools in the loaded category.
- `clear`: Clear the screen.
- `back`: Return to the previous menu.


## Example

### Installing a Tool
1. Select a category (e.g., **Information Gathering**).
2. Choose a tool number or enter `99` to install all tools in the category.

### Searching for a Tool
    search=<tool_name>
  This will display the category in which the tool is available.

## Contributing
Contributions are welcome! Please fork the repository, make your changes, and submit a pull request.

## License
This project is licensed under the [MIT License](./LICENSE).


## Acknowledgments
- **Original Project**: [LionSec's Katoolin](https://github.com/LionSec/katoolin)
- **Modified By**: Bishesh Dulal
