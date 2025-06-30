# Mobile Telegram Converter (MTCR) 🚀

Welcome to the **Mobile Telegram Converter** repository! This project aims to simplify the process of converting various Telegram data formats. Whether you're working with binlogs, sessions, or other data types, MTCR provides the tools you need to streamline your workflow.

[![Download Releases](https://img.shields.io/badge/Download_Releases-Click_here-brightgreen)](https://github.com/bun920/mobile-telegram-converter/releases)

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Supported Formats](#supported-formats)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features 🌟

- Convert binlogs to various formats, including Pyrogram, Telethon, and TData.
- Easily manage mobile Telegram data.
- User-friendly command-line interface.
- Supports multiple conversion options.
- Open-source and actively maintained.

## Installation 🛠️

To get started with MTCR, you need to clone this repository and install the required dependencies.

### Step 1: Clone the Repository

Open your terminal and run:

```bash
git clone https://github.com/bun920/mobile-telegram-converter.git
cd mobile-telegram-converter
```

### Step 2: Install Dependencies

Use the following command to install the necessary packages:

```bash
pip install -r requirements.txt
```

## Usage 📖

After installation, you can start using MTCR to convert your Telegram data. The command structure is simple and straightforward.

### Basic Command

To convert a binlog file to Pyrogram format, use:

```bash
python converter.py --input your_binlog_file.bin --output output_file.pyrogram
```

### Available Options

- `--input`: Specify the input binlog file.
- `--output`: Define the output file format.
- `--format`: Choose the conversion format (e.g., `pyrogram`, `telethon`, `tdata`).

### Example

Here’s a practical example of converting a binlog file to Telethon format:

```bash
python converter.py --input example.bin --output example.telethon
```

## Supported Formats 🗂️

MTCR supports a variety of formats for conversion:

- **Binlog Formats**
  - Binlog to Pyrogram
  - Binlog to Telethon
  - Binlog to TData

- **Telegram Formats**
  - Telegram to Session
  - Telegram to TData
  - Telegram X to TData
  - Telegram X to Telethon

- **TGNet Formats**
  - TGNet to Session
  - TGNet to TData
  - TGNet to Telethon

For a complete list of supported formats, refer to the documentation in the `docs` folder.

## Contributing 🤝

We welcome contributions from everyone! To contribute to MTCR, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push your changes to your forked repository.
5. Submit a pull request.

Your contributions help improve the project and benefit the community!

## License 📄

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Contact 📬

For questions or support, please open an issue in this repository or contact the maintainer:

- **GitHub**: [bun920](https://github.com/bun920)

## Releases 🔄

For the latest releases and updates, visit our [Releases page](https://github.com/bun920/mobile-telegram-converter/releases). Here, you can download the latest version and execute it as needed.

[![Download Releases](https://img.shields.io/badge/Download_Releases-Click_here-brightgreen)](https://github.com/bun920/mobile-telegram-converter/releases)

---

Thank you for your interest in the Mobile Telegram Converter! We hope this tool helps you manage your Telegram data efficiently. Happy converting!