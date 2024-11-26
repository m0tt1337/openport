# OpenPort

OpenPort is a minimalist GUI-based port scanning tool written in Python. It allows users to quickly scan open ports within a specified range on any domain or IP address.

## Features
- **Customizable Port Ranges**: Scan specific ranges of ports, from 1 to 65535.
- **Dynamic Progress Tracking**: See real-time progress as ports are scanned.
- **Simple and Intuitive Interface**: Built using `tkinter` for a clean and responsive GUI.
- **Custom Logo**: Includes a modern and lightweight logo for branding.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/m0tt1337/openport.git
   cd openport
   ```

2. Install dependencies:
   - Ensure you have Python 3.8+ installed.
   - The tool only relies on Python's built-in libraries, so no additional installation is required.

3. Run the application:
   ```bash
   python main.py
   ```

## How to Use
1. Open the tool by running `main.py`.
2. Enter the domain name or IP address you want to scan.
3. Specify the port range (`From Port` and `To Port`).
4. Click **Scan** to begin. The results will appear in the output window, and the progress bar will update in real-time.

## Example
- **Scan all ports from 1 to 500**:
  - Input: `example.com`
  - Range: `1 - 500`
  - Output: Open ports will be listed in the results.

## Screenshot

![Screenshot](https://via.placeholder.com/800x400?text=Screenshot+placeholder)

*(Replace the above URL with an actual screenshot URL if needed.)*

## Contribution
Contributions are welcome! If you encounter any bugs or have ideas for new features:
1. Fork the repository.
2. Create a new branch for your changes.
3. Submit a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Author
Developed by m0tt1337
