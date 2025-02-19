# VS Code Settings

This repository contains my personal Visual Studio Code settings (`settings.json`) and a curated list of recommended extensions to enhance productivity and the overall development experience.

![image](https://github.com/user-attachments/assets/3d94d021-cde1-44b3-b499-31af6bb0230e)

![image](https://github.com/user-attachments/assets/e403b4c3-5c60-429c-82c7-0230f0225156)

## 🔧 Included Settings

The `settings.json` file includes custom configurations for:

- **Editor**: Font, spacing, indentation, and formatting preferences.
- **Terminal**: Font settings and default profile configurations.
- **Explorer**: File and folder organization settings for better navigation.
- **Workbench**: UI customizations, including themes and layout preferences.

## 📌 Installation Guide

Follow these steps to apply these settings to your VS Code environment:

### 1️⃣ Copy `settings.json`

Copy the contents of `settings.json` & `keybindings.json` to your own VS Code settings file, located at:

- **Windows**: `%APPDATA%\Code\User\`
- **MacOS**: `$HOME/Library/Application Support/Code/User/`
- **Linux**: `$HOME/.config/Code/User/`

### 2️⃣ Install Recommended Extensions

Install the recommended extensions listed below for full compatibility with these settings.

## 📦 Recommended Extensions

### 🔹 Essential Extensions

- **ESLint** (`dbaeumer.vscode-eslint`): Integrate ESLint for JavaScript/TypeScript linting.
- **Prettier** (`esbenp.prettier-vscode`): Code formatting with Prettier.
- **Path Intellisense** (`christian-kohler.path-intellisense`): Autocomplete for file paths.
- **NPM Intellisense** (`christian-kohler.npm-intellisense`): Autocomplete for npm modules.
- **DotENV** (`mikestead.dotenv`): Support for `.env` files.
- **Live Server** (`ritwickdey.liveserver`): Launch a local development server with live reload.

### � UI Enhancements

- **Ice Age Theme** (`ganeshgaddhe.ice-age-theme`): A cool color theme for VS Code.
- **Min Theme** (`miguelsolorio.min-theme`): A minimalistic color theme.
- **Simple Light BW** (`mujdecisy.simple-light-bw`): A simple light black-and-white theme.
- **El Product Icon Theme** (`elanandkumar.el-vsc-product-icon-theme`): A modern icon theme for VS Code.
- **Symbols** (`miguelsolorio.symbols`): An icon theme for file symbols.
- **Glassit** (`s-nlf-fh.glassit`): Add transparency to the VS Code window.

### 💻 Development Tools

- **Code Runner** (`formulahendry.code-runner`): Run code snippets in various languages.
- **Docker** (`ms-azuretools.vscode-docker`): Tools for Docker container management.
- **Remote - Containers** (`ms-vscode-remote.remote-containers`): Develop inside Docker containers.
- **Remote - WSL** (`ms-vscode-remote.remote-wsl`): Integrate with Windows Subsystem for Linux (WSL).
- **Rainbow CSV** (`mechatroner.rainbow-csv`): Color highlighting for CSV files.
- **Format JSON** (`clemenspeters.format-json`): Format JSON files easily.

### ⚛️ JavaScript & React

- **Tailwind CSS IntelliSense** (`bradlc.vscode-tailwindcss`): IntelliSense for Tailwind CSS.
- **EJS Support** (`digitalbrainstem.javascript-ejs-support`): Syntax highlighting for EJS files.
- **ES7+ React/Redux/React-Native Snippets** (`dsznajder.es7-react-js-snippets`): Code snippets for React and JavaScript.
- **JavaScript Snippets** (`xabikos.javascriptsnippets`): Useful JavaScript snippets.
- **HTML CSS Class Completion** (`zignd.html-css-class-completion`): Autocomplete for CSS classes in HTML.
- **GraphQL Syntax** (`graphql.vscode-graphql-syntax`): Syntax highlighting for GraphQL.

### 🔧 C/C++ Development

- **C/C++ Compile Run** (`danielpinto8zz6.c-cpp-compile-run`): Compile and run C/C++ code quickly.
- **C/C++ Tools** (`ms-vscode.cpptools`): Official C/C++ support for VS Code.
- **C/C++ Extension Pack** (`ms-vscode.cpptools-extension-pack`): A collection of extensions for C/C++ development.
- **C/C++ Themes** (`ms-vscode.cpptools-themes`): Themes for C/C++ development.

### 🎨 Fun & Productivity

- **Power Mode** (`hoovercj.vscode-power-mode`): Add fun visual effects while typing.
- **Discord Presence** (`icrawl.discord-vscode`): Show your coding activity on Discord.
- **Code Snap** (`adpyke.codesnap`): Capture code as an image.

### 🛠️ Advanced Tools

- **IntelliCode** (`visualstudioexptteam.vscodeintellicode`): AI-assisted code completion.
- **IntelliCode API Usage Examples** (`visualstudioexptteam.intellicode-api-usage-examples`): Examples of API usage powered by IntelliCode.
- **TypeScript Next** (`ms-vscode.vscode-typescript-next`): Support for the latest TypeScript features.

### 📄 Markdown & Documentation

- **Markdown Mermaid** (`bierner.markdown-mermaid`): Render Mermaid diagrams in Markdown files.

---

## 📥 Install Extensions from a File

To install all the recommended extensions at once, use the `extensions.txt` file included in this repository. Run the following command in your terminal:

- **MacOS** & **Linux**:
```sh
cat extensions.txt | xargs -L 1 code --install-extension
```

- **Windows**:
```powershell
Get-Content .\extensions.txt | ForEach-Object { code --install-extension $_ }
```

This will install each extension listed in `extensions.txt` automatically.

## 📌 Notes

- Feel free to customize `settings.json` to better fit your personal workflow.
- Contributions and suggestions are always welcome!
