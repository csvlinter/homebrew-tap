# csvlinter Homebrew Tap

[![Homebrew](https://img.shields.io/badge/homebrew-csvlinter-blue)](https://github.com/csvlinter/homebrew-tap)
[![License](https://img.shields.io/github/license/csvlinter/homebrew-tap)](LICENSE)

> 🍻 Official Homebrew formula for **[csvlinter](https://github.com/csvlinter/csvlinter)** – a blazing-fast, streaming CSV validator with JSON Schema support

**csvlinter** is a high-performance CSV validation tool that processes files in a streaming fashion, making it ideal for validating large datasets without memory constraints. It supports JSON Schema validation for comprehensive data quality checks.

---

## Quick Installation

```bash
# Add the csvlinter tap (one-time setup)
brew tap csvlinter/tap

# Install csvlinter
brew install csvlinter
```

## Upgrade

```bash
# Upgrade to the latest version
brew upgrade csvlinter
```

## 🛠️ Usage

Once installed, you can start validating CSV files immediately:

```bash
# Basic validation
csvlinter your-file.csv

# Validate with JSON Schema
csvlinter --schema schema.json your-file.csv

# Get help
csvlinter --help
```

For comprehensive usage instructions and examples, visit the [csvlinter documentation](https://github.com/csvlinter/csvlinter).

## Requirements

- macOS 10.12+ or Linux
- Homebrew package manager

## 🔗 Related Projects

- **[csvlinter](https://github.com/csvlinter/csvlinter)** - Main project repository
- **[csvlinter VSCode Extension](https://github.com/csvlinter/vscode-extension)** - Visual Studio Code extension for csvlinter
- **[csvlinter-action](https://github.com/csvlinter/csvlinter-action)** - GitHub Action for CI/CD pipelines

## License

This Homebrew tap is licensed under the same terms as the main csvlinter project.

## Contributing

Issues and pull requests are welcome! Please visit the [main repository](https://github.com/csvlinter/csvlinter) for feature requests and bug reports.