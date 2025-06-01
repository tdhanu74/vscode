# Visual Studio Code with integrated Cline Extension

## Steps for local development

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```
3. Install dependencies for Cline extension:
   ```bash
   cd extensions/cline
   npm run install:all
   npm run package
   ```
4. Install and compile all vscode dependencies:
   ```bash
   npm run compile
   ```
5. Use the below command for local testing:
   ```bash
   npm run watch
   ./script/code.sh
   ```
6. Use below command for build:
   ```bash
   npm run gulp vscode-win32-x64
   ```
