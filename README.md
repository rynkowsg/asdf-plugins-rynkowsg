# asdf-plugins-rynkowsg

asdf-plugins-rynkowsg is a collection of plugins I made for [asdf](https://asdf-vm.com) version manager.

## Plugins

| Tool / Language              | Plugin Repository                           |
|------------------------------|---------------------------------------------|
| [clj-kondo]                  | [rynkowsg/asdf-clj-kondo][asdf-clj-kondo]   |
| [garden-cli]                 | [rynkowsg/asdf-garden-cli][asdf-garden-cli] |
| [jet]                        | [rynkowsg/asdf-jet][asdf-jet]               |
| [opentofu][opentofu-website] | [rynkowsg/asdf-opentofu][asdf-clj-opentofu] |
| a generic Python Application | [rynkowsg/asdf-pyapp][asdf-pyapp]           |

[clj-kondo]: https://github.com/clj-kondo/clj-kondo
[garden-cli]: https://github.com/nextjournal/garden-cli
[jet]: https://github.com/borkdude/jet
[opentofu-website]: https://opentofu.org/

[asdf-clj-kondo]: https://github.com/rynkowsg/asdf-clj-kondo
[asdf-clj-opentofu]: https://github.com/rynkowsg/asdf-opentofu
[asdf-garden-cli]: https://github.com/rynkowsg/asdf-garden-cli
[asdf-jet]: https://github.com/rynkowsg/asdf-jet
[asdf-pyapp]: https://github.com/rynkowsg/asdf-pyapp

## Development - handy commands

**Add new module**

```bash
git submodule add --name rynkowsg/asdf-jet git@github.com:rynkowsg/asdf-jet.git plugins/jet
```
