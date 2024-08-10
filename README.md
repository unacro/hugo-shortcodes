# Hugo Shortcodes

Custom [Shortcodes of Hugo](https://gohugo.io/content-management/shortcodes/)

## Usage

Edit `config/_default/module.toml`:

```toml
[[imports]]
disable = false
path = "github.com/unacro/hugo-shortcodes"
```

Then run `hugo server` to download automatically.

## Update

```bash
hugo mod get -u
```
