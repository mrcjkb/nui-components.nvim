# nui-components.nvim &middot; [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com) [![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg?style=flat-square)](https://github.com/your/your-project/blob/master/LICENSE)

<img src="https://raw.githubusercontent.com/grapp-dev/nui-components.nvim/main/assets/nui-components-logo.png" alt="nui-components.nvim" align="right">

> A powerful tool that aims to make UI development in Neovim more accessible, intuitive, and enjoyable.

NuiComponents is a library built on top of [`nui.nvim`](https://github.com/MunifTanjim/nui.nvim), which provides an extensive set of tools for creating user interfaces in Neovim using Lua. With NuiComponents, developers can easily build complex UIs using a simple and intuitive API, which supports various UI elements. Moreover, the library includes advanced features like state management and form validations.

## Installation

To install NuiComponents, you should use your preferred plugin manager.

[Lazy](https://github.com/folke/lazy.nvim)

```lua
{
  "grapp-dev/nui-components.nvim",
  dependencies = {
    "MunifTanjim/nui.nvim"
  }
}
```

[Packer](https://github.com/wbthomason/packer.nvim)

```lua
use {
  "grapp-dev/nui-components.nvim",
  requires = {
    "MunifTanjim/nui.nvim"
  }
}
```

## Documentation

Full documentation can be found [here](https://nui-components.grapp.dev).

## License

The MIT License.

See [LICENSE](LICENSE)

