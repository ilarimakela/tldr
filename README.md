# tldr
Simplified and community-driven man pages http://tldr-pages.github.io/

## Usage

    Usage: tldr [command]

Example:

    tldr grep

## Installation

    mkdir -p ~/bin
    curl -o ~/bin/tldr https://raw.githubusercontent.com/ilarimakela/tldr/master/tldr
    chmod +x ~/bin/tldr

Then make sure `~/bin` is in your `$PATH`. On OSX edit ~/.bash_profile (or ~/.bashrc on Linux), and add the following line to the bottom of the file:

    export PATH=~/bin:$PATH

## Requirements
- curl
- unzip
- python2.7
- py markdown (pip install markdown)
- py pygments (pip install pygments)
- py yaml (pip install yaml)

