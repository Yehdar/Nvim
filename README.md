# nvim-config
My config files for neovim. As of right now, it works but a lot of plugins still need to be added.

## future references
If a plugin is not working, delete it and then install it again. Most likely, something went wrong during installation. Anyways, cd into `.local/share/nvim/site/pack/parker/start` and delete the plugin with `rm -rf [name]`. Afterwards, delete the file from `after/plugin` and the code in `packer.lua` file found in `lua/yehdar/packer.lua`. You can begin again with a clean slate!
