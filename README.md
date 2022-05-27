1. Install neovim with homebrew

- brew install --HEAD tree-sitter luajit neovim

2. Install vim plug

   - curl -fLo ~/.local/share/nvim/site/autoload/plug.vim --create-dirs https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim

3. Install neovim-npm package and python package

```python
pip3 install --user neovim
```

```javascript
yarn global add neovim
```

4. Run 
```vim
:PlugInstall
```

```vim
:CocInstall  coc-json coc-html coc-css coc-prettier coc-pyright coc-snippets
```

5. Install tailwindcss with language Server Protocol (lsp)

6. Install typescript with language Server Protocol (lsp)

7. Install emmet for reactjs, html, typescriptreact with language Server Protocol (lsp)


```vim
:LspInstall tailwindcss
:LspInstall typescript -- select option 3
:LspInstall emmet_ls
```

6. Copy files to required directories

```bash
cp -rf ultisnips ~/.config/coc
cp -rf * ~/.config/nvim
```
