# webrtc-file-transfer

![JavaScript](https://img.shields.io/badge/JavaScript-ES2024-yellow?logo=javascript) ![License](https://img.shields.io/badge/License-MIT-green) ![Status](https://img.shields.io/badge/Status-Active-brightgreen)

Browser-based encrypted P2P file transfer with no server storage.

## Overview

This tool provides a production-ready implementation focused on performance, security, and developer experience. Built with modern best practices and designed for real-world deployment.

## Features

- **High performance** — optimized for low latency and high throughput
- **Production ready** — proper error handling, logging, and observability
- **Well tested** — unit and integration tests included
- **Easy to deploy** — Docker support out of the box

## Installation

```bash
git clone https://github.com/abubakar-99/webrtc-file-transfer
cd webrtc-file-transfer
npm install
```

## Usage

```bash
node src/index.js
```

## Architecture

```
webrtc-file-transfer/
├── src/
│   ├── main.js
│   ├── core/
│   └── utils/
├── tests/
├── docs/
├── Dockerfile
└── README.md
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first.

## License

[MIT](LICENSE)
