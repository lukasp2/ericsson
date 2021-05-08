# Vertel
Additional tools for development at Vertel

## Install and uninstall
```
wget -O- https://raw.githubusercontent.com/lukasp2/vertel/main/install | bash
```
```
wget -O- https://raw.githubusercontent.com/lukasp2/vertel/main/uninstall | bash
```

## Tools
* **lpbackup** - create a backup of a database \
usage: `lpbackup [DATABASE]`

## Extra
* **lpps1** - a PS1 git branch indicator \
usage: `lpps1 [OPTIONS]`
```
OPTIONS:
-t, --temporary: set PS1 environment variable in this shell only (default)
-p, --permanent: set PS1 environment variable in ~/.bash_aliases
```

## Upcomming
* **lpupdm** - odooupdm with input validation (checks if db and modules exist), whitespace support and better output \
usage: `lpupdm [DB] [MODULE] ...`
