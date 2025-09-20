# neovim-ocaml-quickstart

This is a starter pack for OCaml development in Neovim. It provides a minimal but effective setup for OCaml development, including LSP support, formatting, and completion.

## Features

*   **LSP Support**: Integrated with `ocamllsp` for features like go-to-definition, type hints, and more.
*   **Formatting**: Uses `ocamlformat` to automatically format your code on save.
*   **Completion**: Provides completion with `blink.cmp`.
*   **Plugin Management**: Uses `lazy.nvim` for easy plugin management.

## Prerequisites

*   [Neovim](https://neovim.io/) (v0.9.0 or later)
*   [OCaml](https://ocaml.org/docs/install.html)
*   [opam](https://opam.ocaml.org/doc/Install.html)
*   [ocaml-lsp](https://github.com/ocaml/ocaml-lsp) (`opam install ocaml-lsp-server`)
*   [ocamlformat](https://github.com/ocaml-ppx/ocamlformat) (`opam install ocamlformat`)

## Installation

1.  Clone this repository to your Neovim configuration directory (usually `~/.config/nvim`).
2.  Start Neovim. The plugins will be installed automatically.

## Usage

*   The LSP client will automatically start when you open an OCaml file.
*   Code will be formatted on save if you have a `.ocamlformat` file in your project.
*   Completion will be triggered automatically as you type.

## Configuration

The configuration is in the `init.lua` file. You can customize it to your liking.

## Where to go from here?

* This configuration is done in a single file, as your neovim config grow, it will be easier to manage if you use a structured directory approach. [The Only Video You Need to Get Started with Neovim](https://youtu.be/m8C0Cq9Uv9o?si=FYYXmVNKYd18RD5F)
* Many plugins have OCaml support, give them a try. See for example [Friendly snippets](https://github.com/rafamadriz/friendly-snippets) or [Text object](https://github.com/nvim-treesitter/nvim-treesitter-textobjects)
