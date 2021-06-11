# hred

Small tool which makes config files with tons of comments acutally readable.

## Installation

1. Clone this repo
2. Navigate to it in your terminal
3. Copy it into your path, renaming it without the `.sh` extension.
    * Example: `cp hred.sh /usr/local/bin/hred`
4. Make the file executable.
    * Example: `chmod +x hred`

## Usage

Simply use `hred <file>` and all commented lines will be removed, spitting out text representing the active configuration. 

`hred ~/.zshrc`

You can also pipe output to `hred`.

`cat ~/.zshrc | hred`
