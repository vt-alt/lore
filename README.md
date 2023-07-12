# lore
lore.kernel.org query reader in [Neo]Mutt.

## Usage
```shell
lore --help OR commitish OR lore search query
```

## Requirements
* Kernel source git repo (in `~/src/linux`).
* `curl` for web requests.
* `formail` tool to deduplicate mbox.

## References
Yes I'm aware of existence `lei` tool:
* https://people.kernel.org/monsieuricon/lore-lei-part-1-getting-started
* https://people.kernel.org/monsieuricon/lore-lei-part-2-now-with-imap

`lore` tool is simpler and written in bash.
