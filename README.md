# Windows Fonts Archive

This repository contains a collection of system fonts from various versions of Microsoft Windows, spanning from Windows XP to Windows 11.

## Installation

### Windows
1. Download the desired font file
2. Right-click the font file and select "Install" or "Install for all users"
3. Alternatively, copy the font files to `C:\Windows\Fonts`

### macOS
1. Download the font file
2. Double-click to open in Font Book
3. Click "Install Font"

### Linux
1. Copy font files to `~/.fonts` or `/usr/share/fonts`
2. Run `fc-cache -f -v` to refresh font cache

## Compatibility Notes

- .FON bitmap fonts have limited cross-platform support and are primarily for Windows systems
- .TTC files are well-supported across modern operating systems
- Some legacy fonts may not render correctly on modern high-DPI displays

## Use Cases

- Software testing and compatibility verification
- Historical research and digital preservation
- Running legacy applications that require specific Windows fonts
- Typography and font design reference
- Virtual machine and emulator setups

## Contributing

Contributions are welcome. If you have system fonts from other Windows versions or variants not included here, please open an issue or pull request.

## Disclaimer

This repository is not affiliated with or endorsed by Microsoft Corporation. All trademarks and copyrights belong to their respective owners.