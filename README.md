1. 切换到家目录后 `git clone https://github.com/zhangxinyuan07/.vim.git`
2. 在家目录下创建vimtmpfiles文件夹, 并在其中创建undo, swp和backup三个文件夹
3. Windows : 在家目录下创建_vimrc文件,并写入 `source ~/.vim/.vimrc`
4. Linux : `ln -s ~/.vimrc ~/.vim/.vimrc`
5. Install LLVM (clangd language server)
6. neovim：
   - Install neovim
   - Install pip3, and do pip3 install --user pynvim
   - Install node, and do npm install -g neovim
   - Install FiraCode
   - 在 "~/AppData/Local/nvim" 目录下新建 init.vim文件并写入 `source ~/.vim/.vimrc`
