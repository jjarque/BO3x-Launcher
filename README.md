## BO3xLauncher

Open-source launcher for Black Ops 3 with dedicated server support and improved anticheat.

GitHub Release: https://github.com/jjarque/BO3x-Launcher/releases/latest

## Quick Start

1. Download BO3xLauncher.exe from releases
2. Run the executable
3. Launcher auto-detects BO3 installation (Comes also with an option to manually select the BO3 path)  
4. Login/Register then browse servers

Requires legitimate Black Ops 3 copy.

## Features

- Steam BO3 auto-detection
- Master server browser
- JWT authentication system
- One-click dedicated server joining
- Open source - full transparency

## Requirements

- OS: Windows 10/11 (x64)
- BO3: Legitimate copy
- .NET: 8.0 Desktop Runtime (included)

## Legal Notice

BO3xLauncher contains no Black Ops 3 files.
Only works with legitimate installations.
Full legal details: docs/LEGAL.md

## Build from Source

- git clone https://github.com/jjarque/BO3x-Launcher.git
- cd src
- dotnet restore
- dotnet publish -c Release -r win-x64 --self-contained -p:PublishSingleFile=true -o dist/

## Contributing

1. Fork the project
2. Create feature branch
3. Commit changes
4. Push to branch
5. Open Pull Request

## Documentation

Documentation is still in progress. For now, please refer to the source code and comments for guidance.

## Development Status

- Launcher UI: TBD
- Backend API: TBD
- Client Anticheat: TBD
- Server Tools: TBD

## Credits

Built by jjarque