# MediaWiki Vim Plugin for In-Editor Vim Experience (Work in Progress)

## Overview

This MediaWiki Vim Plugin enhances your editing experience within the MediaWiki editor by bringing Vim functionality directly into the browser. It utilizes JavaScript to simulate the Vim environment, allowing you to leverage familiar Vim keybindings and commands for efficient and streamlined editing.

### Features

- **Vim Keybindings**: Enjoy the power of Vim's modal editing within the MediaWiki editor.
- **Normal Mode**: Navigate, delete, and manipulate text using Vim's normal mode.
- **Insert Mode**: Enter text seamlessly with Vim's insert mode.
- **Visual Mode**: Select and manipulate text visually using Vim's visual mode.
- **Customizable Settings**: Configure the plugin to match your preferred Vim settings.

## Installation

Follow these steps to install the MediaWiki Vim Plugin:

1. **Download**: Clone or download the plugin repository.

    ```bash
    git clone git@github.com:YvarRavy/MediaWikiVim.git
    ```

2. **Integration**: Include the plugin files in your MediaWiki environment.

    ```bash
    cp -r MediaWikiVim/* /path/to/mediawiki/extensions/VimPlugin/
    ```

3. **Configuration**: Add the following configuration to your `LocalSettings.php` file:

    ```php
    wfLoadExtension( 'VimPlugin' );
    ```

4. **Enable**: Enable the plugin through the MediaWiki extension manager.

## Usage

Once the plugin is installed and enabled, you can start using Vim-like editing within the MediaWiki editor.

### Basic Commands

- **Switch to Normal Mode**: Press `Esc` to enter normal mode.
- **Switch to Insert Mode**: Press `i` in normal mode to enter insert mode.
- **Save Changes**: Press `:w` in normal mode to save changes.
- **Quit Editor**: Press `:q` in normal mode to exit the editor.

### Customization

You can customize the plugin settings to match your preferred Vim configuration. Edit the `VimPlugin.js` file to modify keybindings, behavior, and other settings.

## Contributions

Contributions are welcome! If you encounter issues or have suggestions for improvements, feel free to open an issue or submit a pull request on the [GitHub repository](git@github.com:YvarRavy/MediaWikiVim.git).

## Work in Progress

This project is currently in progress, and active development is ongoing. Feel free to check back for updates and improvements.

## License

This MediaWiki Vim Plugin is licensed under the [MIT License](LICENSE). Feel free to use, modify, and distribute it according to the terms of the license.

## Acknowledgments

Special thanks to the Vim community for inspiration and guidance in creating this plugin.

---

Happy editing with Vim in your MediaWiki environment!

