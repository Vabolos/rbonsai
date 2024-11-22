# rbonsai

This program is currently unfinished!

`rbonsai` is a port of [`cbonsai`](https://gitlab.com/jallbrit/cbonsai), written in Rust (hence the "r").

## Installtion

To install via [crates.io](https://crates.io/crates/rbonsai) run `cargo install rbonsai`.

## Usage
```
Usage: rbonsai [OPTIONS]

Options:
  -l, --live                     Whether the tree generation should pause after each step to allow the user to watch it grow
  -t, --time <TIME>              In live mode, wait time in seconds between each step of growth [default: 0.03]
  -i, --infinite                 Infinite mode: keep growing trees
  -w, --wait <WAIT>              In infinite mode, the wait time in seconds between each tree [default: 4]
  -S, --screensaver              Screensaver mode: equivalent to -li and quit on any keypress
  -m, --message <MESSAGE>        Attach message next to tree
  -b, --base <BASE>              Ascii art plant base to use [default: 1]
  -M, --multiplier <MULTIPLIER>  The branch multiplier; higher -> less branches [default: 3]
  -L, --life <LIFE>              The starting life of the tree higher -> bigger tree [default: 32]
  -p, --print                    The starting life of the tree higher -> bigger tree
  -s, --seed <SEED>              random number seed for reproducable trees
  -v, --verbose                  Whether there should be debug prints
  -h, --help                     Print help
  -V, --version                  Print version
```

## License

This code is licensed under the GNU GPLv3 license, see `LICENSE`.
This is due to the fact that this code is partially ported from `cbonsai`, which is licensed under the GNU GPLv3 license.

## Contributing

Feel free to contribute!

## Inspiration

This project *also* wouldn't be here if it weren't for its roots!
`rbonsai` is a Rust version of `cbonsai`.
`cbonsai` is itself a newer version of [bonsai.sh](https://gitlab.com/jallbrit/bonsai.sh), which was written in `bash` and was itself a port of [this bonsai tree generator](https://avelican.github.io/bonsai/) written in `javascript`.
