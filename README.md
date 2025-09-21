# pz-snippets

Simple extension that adds code snippets for Project Zomboid scripting. Mainly creating item and recipe scripts.

## Installation

Download the [latest release](https://github.com/doomercreatine/pz-snippets/releases/latest). Then in VSCode navigate to extensions `CTRL + SHIFT + X` on Windows. Then at the top right of the Extensions panel select `...` -> `Install from VSIX...`. Select the file and verify it has installed. VSCode might need to be restarted for it to take effect.

## Features

Supports Project Zomboid Script Support and ZedScript extensions. Automatically enables if workspace contains `media/scripts/` or `media/lua`

Snippets available:

- .new -> Use with both item and recipe scripts to define module and imports
- .item -> Use for items to create the skeleton item definitions
  - .fluidcontainer -> Use within .item to define fluidcontainer component.
- .recipe -> Craft recipe skeleton.

## Known Issues

Report issues on [GitHub](https://github.com/doomercreatine/pz-snippets/issues)

## Release Notes

### 0.0.1

Initial release of pz-snippets

**Enjoy!**
