# Murex module: terminal-user-agent

This _murex_ module creates a data type for URLs (`url`) and creates an open
handler which renders those websites in the terminal.

It also creates a `config` option to select which HTTP client to fetch and
render those links:

    » config set open url

Lastly two additional functions are created, `http` and `https` which allow you
to paste URLs directly into the terminal. eg

    » https://github.com/lmorg

This works thanks to `:` being a special token for splitting the function name
and arguments.