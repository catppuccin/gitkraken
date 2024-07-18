# Contributing

Thank you for taking a look at how to contribute to this repository! We appreciate your time and effort to make this project better.

## Guidelines

- `*.jsonc` files must be compiled from `gitkraken.tera` (see [Compiling](#compiling)). No manual editing of the jsonc files is required.
- No syntax errors in `gitkraken.tera` are required.
- Latte/Frappe/Macchiato/Mocha Screenshot ([Catwalk](https://github.com/catppuccin/catwalk) @ [Toolbox Repo](https://github.com/catppuccin/toolbox)) is required.

## Compiling

This project uses the [Whiskers](https://github.com/catppuccin/whiskers) templating engine starting from version 1.0.0. This enables you to add your own color overrides if needed.

To reprocess the jsonc files:

- Download and install [Whiskers](https://github.com/catppuccin/whiskers).
- Clone this repository.
- Run `whiskers ./gitkraken.tera` in the root of the project.

Once this is done, the jsonc files in the `./themes` folder will be ready to be used.

&nbsp;

<p align="center"><img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/footers/gray0_ctp_on_line.svg?sanitize=true" /></p>
<p align="center">Copyright &copy; 2021-present <a href="https://github.com/catppuccin" target="_blank">Catppuccin Org</a></p>
<p align="center"><a href="https://github.com/catppuccin/catppuccin/blob/main/LICENSE"><img src="https://img.shields.io/static/v1.svg?style=for-the-badge&label=License&message=MIT&logoColor=d9e0ee&colorA=363a4f&colorB=b7bdf8"/></a></p>
