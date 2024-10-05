# Arduino with Neovim

This is a simple guide to setup Neovim for Arduino development.

## Requirements

- PlatformIO

## Setup

- On neovim run `:Pioinit` to select the board you are using.
- run `pio run -t compiledb` to make the lsp work
- run `:Piorun build` to compile the code
- run `:Piorun` to compile the code and upload it to the board
