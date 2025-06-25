# Omnic Services: PC Optimization Scripts

## How to Use

1. Install [WSL and Ubuntu](https://learn.microsoft.com/en-us/windows/wsl/install).
2. Download this folder and place it somewhere on your PC.
3. Open Ubuntu (WSL) and navigate to the folder:
   ```bash
   cd "/mnt/c/Users/yourusername/Downloads/Omnic V2"
   ```
4. Convert scripts to Unix format (once, inside Ubuntu/WSL):
   ```bash
   sudo apt update
   sudo apt install dos2unix
   dos2unix *.sh
   ```
5. Run the main script:
   ```bash
   sudo bash omnic-services.sh
   ```
6. Follow the on-screen menu for optimizations.

## Notes

- Only run scripts from sources you trust.
- You can restore defaults at any time using the menu.
