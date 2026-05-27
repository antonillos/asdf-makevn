# asdf-makevn

asdf plugin for [makevn](https://github.com/antonillos/makevn).

## Install

```sh
asdf plugin add makevn https://github.com/antonillos/asdf-makevn.git
asdf install makevn latest
MAKEVN_VERSION="$(asdf latest makevn | sed -n '$p')"
asdf set -u makevn "${MAKEVN_VERSION}"
```

## MCP

Use the installed `makevn-mcp` binary as the MCP server command.
