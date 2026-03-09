# PinkCatBoo-Personal-Edit

A personal edit of the Pink-Cat-Boo theme for Visual Studio Code, featuring a dark UI theme with a pink color scheme.

## Installation

- Download the `.vsix` file from the [releases](https://github.com/VanillaMeow/PinkCatBoo-Personal-Edit/releases) page.
- Inside VSCode, open the Command Palette (default `Ctrl+Shift+P`).
- Type and select "Install from VSIX...".
- Select the downloaded `.vsix` file.

## Development Setup

You need to have the following dependencies installed:

- [Git](https://git-scm.com/)
- [Yarn](https://yarnpkg.com/)

```sh
# 1. Clone the repository
git clone https://github.com/VanillaMeow/PinkCatBoo-Personal-Edit.git
cd PinkCatBoo-Personal-Edit

# 2. Install dependencies
yarn install

# 3. Edit `themes/pink-cat-boo-edit.json`
code .

# 4. Build the VSIX package
yarn package

# 5. Inside VSCode run "Install from VSIX..."
#    and select the generated `.vsix` file in the project root.

```
