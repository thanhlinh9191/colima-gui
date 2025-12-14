# Colima GUI

> **Note:** This is a fork of [kyletaylored/colima-gui](https://github.com/kyletaylored/colima-gui) with updates for compatibility with Colima v0.9.1 and modern dependencies.

Colima GUI is a desktop application for managing Colima, a tool that provides container runtimes on macOS with minimal setup. This application offers a graphical user interface for starting, stopping, restarting, and managing Colima instances.

## Features

- Start, stop, and restart Colima instances
- Check the status of Colima
- Delete and prune Colima instances
- List Colima instances
- Edit Colima configuration
- View Colima version

## Installation

### Prerequisites

- [Node.js](https://nodejs.org/) (v16 or later)
- [Rust](https://www.rust-lang.org/tools/install) (latest stable version)
- [Tauri CLI](https://tauri.studio/en/docs/getting-started/intro#setting-up-your-environment)

### Steps

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/colima-gui.git
   cd colima-gui
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Run the application in development mode:

   ```bash
   npm run tauri dev
   ```

4. Build the application for production:

   ```bash
   npm run tauri build
   ```

## Usage

Once the application is running, you can use the provided buttons to manage your Colima instances. The terminal output will display the results of the commands executed.

## What's New in This Fork

This fork includes the following improvements:

- ✅ Updated to work with Colima v0.9.1
- ✅ Upgraded React from v17 to v18 with new `createRoot` API
- ✅ Fixed Tauri IPC configuration issues
- ✅ Added `-f` flag to prune command for non-interactive execution
- ✅ Removed incompatible dependencies
- ✅ Fixed window parameter handling in frontend

## Credits

This project is a fork of the original [Colima GUI](https://github.com/kyletaylored/colima-gui) created by [Kyle Taylor](https://github.com/kyletaylored). Thanks to Kyle for creating the initial version of this application.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

If you have any questions or issues, please open an issue in this repository.

## Recommended IDE Setup

- [VS Code](https://code.visualstudio.com/) + [Tauri](https://marketplace.visualstudio.com/items?itemName=tauri-apps.tauri-vscode) + [rust-analyzer](https://marketplace.visualstudio.com/items?itemName=rust-lang.rust-analyzer)

