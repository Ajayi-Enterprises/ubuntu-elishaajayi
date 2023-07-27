# Ubuntu-elishaajayi
# Dotfiles Repository

This repository contains my personal dotfiles and configurations for Linux, including settings for Vim, shell, and other tools. With these dotfiles, I can quickly set up a familiar environment on any new PC or Linux installation.


### Prerequisites

To use these dotfiles, you'll need the following software installed on your system:

- Git
  ```bash
  
- Vim (or Neovim)
- Shell (bash, zsh, etc.)

### Installation

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/Ajayi-Enterprises/ubuntu-elishaajayi.git

2. Move the .vimrc file to root folder
3. Enable Vbundle
   ```bash
   mkdir -p ~/.vim/bundle
   cd ~/.vim/bundle
   git clone https://github.com/VundleVim/Vundle.vim.git Vundle.vim

4. Run the command PluginInstall
   ```bash
   vim +PluginInstall +qall

5. Check if everything works by creating a simple c file
   ```bash
   # Creating the file
   vim example.c +wq
   # Opening the file
   vim example.c

6. Try typing the following
   ```c
   #include <stdio.h>

   int main(void) {
      // You can edit this code as you like to see if anything breaks
      printf("Testing\n");
      return 0;
   }
   

Usage
With the dotfiles in place, you can enjoy your familiar settings and configurations on any new PC or Linux installation. Make sure to keep the repository up-to-date with any changes you make to your configurations.

