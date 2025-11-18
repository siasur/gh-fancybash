# FancyBash

**Disclaimer:** This project is designed specifically for the game **Grey Hack** and is not intended for real-world use.

## About FancyBash

FancyBash is a more feature-rich and visually appealing alternative to the default bash shell provided in Grey Hack. It is designed as a drop-in replacement, offering additional functionality and customization options to improve your in-game scripting experience.

## Features

- **Custom `.bashrc` Support:** FancyBash reads a `.bashrc` file located in the user's home directory. This file allows you to define a `PATH` variable, enabling greater control over your environment.

- **Enhanced Prompt:** FancyBash includes a fancier prompt. While currently static, future updates aim to make the prompt more informative and fully customizable.

## Building and Installing

Due to the way Grey Hack handles `import_code` calls, FancyBash requires some additional steps to integrate into the game:

1. **Using Greybel:** The easiest way to build and install FancyBash is by using the Greybel extension vor VS Code, which automatically generates a "installer" file, that can be copied over into the game.

2. **Manual Installation:** If you prefer, you can manually adjust the files to conform to Grey Hack's requirements. This involves ensuring all `import_code` calls are only happening in the entry file.

Enjoy your enhanced Grey Hack experience with FancyBash!