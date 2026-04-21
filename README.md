# RetroShare

RetroShare is a decentralized, private, secure, cross-platform communication toolkit.
RetroShare provides file sharing, chat, messages, forums, channels, boards and more.

[![GitHub release](https://img.shields.io/github/release/retroshare/retroshare.svg?label=latest%20release)](https://github.com/RetroShare/RetroShare/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/retroshare/retroshare/total)](https://github.com/RetroShare/RetroShare/releases/latest)

## Features

- **Friend-to-Friend Network**: Connect directly with friends without centralized servers
- **File Sharing**: Share files with colleagues and friends securely
- **Chat & Messaging**: Private messaging and group chats
- **Forums & Channels**: Discussion forums and channels
- **Cross-Platform**: Available on Windows, macOS, Linux, and Android

## Getting Started

### Prerequisites

- Qt 5.15+ or Qt 6.x
- OpenSSL 1.1.x or 3.x
- CMake 3.16+
- A C++20 compatible compiler

### Building

Clone the repository and its submodules:

```bash
git clone https://github.com/RetroShare/RetroShare.git
cd RetroShare
git submodule update --init --remote --force libbitdht/ libretroshare/ openpgpsdk/
```

See the [build_scripts](build_scripts) directory for platform-specific build instructions.

## License

RetroShare is released under the [GNU GPL v2+](LICENSES) with portions under various open-source licenses.
