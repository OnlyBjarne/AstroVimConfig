# AstovimConfig
User-configs for astrovim setup

# Install

1. Clone AstroNvim (normal installation instructions)

`git clone https://github.com/AstroNvim/AstroNvim ~/.config/nvim`

2. Clone your empty new repository to your ~/.config/nvim/lua folder

```git clone https://github.com/OnlyBjarne/astrovimconfig.git ~/.config/nvim/lua/user```

3. Initialize AstroNvim

`nvim  --headless -c 'autocmd User PackerComplete quitall' -c 'PackerSync'`
