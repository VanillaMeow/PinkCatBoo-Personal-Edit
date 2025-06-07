# Pink-Cat-Boo-Leah

A personal edit of the Pink-Cat-Boo theme for Visual Studio Code, featuring a dark UI theme with a pink color scheme.

## Development Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/YehaNeko/PinkCatBoo-Personal-Edit.git
   cd PinkCatBoo-Personal-Edit
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Make your theme modifications in the `themes/pink-cat-boo-edit.json` file.

4. Package the theme:

   ```bash
   npm run package
   ```

   This will create a `.vsix` file in the root directory.

5. Install the theme locally:
   - Open VS Code.
   - Open the Command Palette (default `Ctrl+Shift+P`).
   - Type "Install from VSIX".
   - Select the generated `.vsix` file.
