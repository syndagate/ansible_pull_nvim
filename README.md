# ansible_pull_nvim

## Preconditions
Debian based distro with git and ansible installed
```bash
sudo apt install git ansible
```
## Usage
```bash
sudo ansible-pull -U https://github.com/syndagate/ansible_pull_nvim.git -C master
```
## Description
This installs neovim version 0.92. It will also installs some plugins:

* https://github.com/VonHeikemen/lsp-zero.nvim
* https://github.com/folke/neoconf.nvim
* https://github.com/folke/neodev.nvim
* https://github.com/hrsh7th/nvim-cmp
* https://github.com/neovim/nvim-lspconfig
* https://github.com/nvim-treesitter/nvim-treesitter
* https://github.com/nvim-telescope/telescope.nvim
* https://github.com/folke/tokyonight.nvim
* https://github.com/vim-airline/vim-airline
* https://github.com/folke/which-key.nvim

Feel free to fork this repo and adjust it to your needs. Above all, the users in the 'host_vars/localhost.yml' file should be adapted to your needs.
## Screenshots
![](example01.png?raw=true)
