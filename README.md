# Neovim


## How to customized the clangd config on the nvim-lsp

### user configuration: a config.yaml file in an OS-specific directory:

```

Windows: %LocalAppData%\clangd\config.yaml, typically C:\Users\Bob\AppData\Local\clangd\config.yaml.

macOS: ~/Library/Preferences/clangd/config.yaml

Linux and others: $XDG_CONFIG_HOME/clangd/config.yaml, typically ~/.config/clangd/config.yaml.

```

### use a .clangd in the root folder

Add .clangd in your root dir

```


CompileFlags:
    Add: [-std=c++20]
```
 [config](https://www.reddit.com/r/neovim/comments/vozezj/how_to_set_clangd_c_diagnostic_version/)
 
 [llvm_cland web](https://clangd.llvm.org/config)



---


## Clang-formater config

### linux MAC 

copy the **.clang-format** file from this git, copy to the $Home folder, the clang-format nvim plug will look for this, any folder under $HOME, even a sub folder will pick up the configuration

### windows

copy the **.clang-format** file to c:/

 [clang-format-configurator](https://zed0.co.uk/clang-format-configurator/)



