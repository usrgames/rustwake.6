# rustwake

The releases of rustwake, a first-person shooter for the terminal from [usr.games](https://usr.games): clear the rogue machines out of a dark plant, one map at a time. Its page is [usr.games/rustwake](https://usr.games/rustwake), where it also plays in the browser.

This repository holds what a player downloads, and none of the game's source.

## Install

With [tty1](https://usr.games/tty1), the usr.games launcher:

```
tty1 install rustwake
```

Or by hand, from the [latest release](https://github.com/usrgames/rustwake.6/releases/latest): take the archive for your system, `rustwake_OS_ARCH.tar.gz` (`darwin` or `linux`, `arm64` or `amd64`), with `manifest.json` and `manifest.json.sig`. Check them as [KEYS.md](https://github.com/usrgames/usr.games/blob/main/KEYS.md#check-a-release-by-hand) says, then unpack the archive and run `./rustwake`. Its manual page, `rustwake.6`, is in the archive too.

It needs a terminal that shows true color, 80 columns by 24 rows or more.

## Report a fault

[Open an issue](https://github.com/usrgames/rustwake.6/issues/new) here. Say what you did, what happened, which terminal you use, and what `rustwake -version` prints.

## License

You may download rustwake, install it and play it, free of charge; [LICENSE](LICENSE) is the whole of what it allows. [NOTICES](NOTICES) holds the licences of Go and of the modules the game is built from.
