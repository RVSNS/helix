# helix

Personal [Helix](https://helix-editor.com) editor configuration, tracked in git.

## Layout

- `config.toml` — editor settings, theme, keymaps
- `languages.toml` — per-language overrides (LSP, formatters, etc.)

## Usage

Symlink or clone this repo to `~/.config/helix`:

```sh
git clone https://github.com/RVSNS/helix.git ~/.config/helix
```

## Language server dependencies

Helix shells out to external LSP binaries; they aren't vendored in this repo.

| Language    | Server                 | Install                                  |
|-------------|-------------------------|-------------------------------------------|
| sh / bash   | `bash-language-server`  | `npm install -g bash-language-server`     |

Make sure your npm global bin directory is on `$PATH` (e.g. `npm config get prefix`).

