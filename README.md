# Yorkie

A pure-Bash port of [Husky](https://typicode.github.io/husky/). Woof!

## Installation

Simply download [`yorkie`](yorkie) and put it somewhere in your `PATH`.

Alternatively, use [asdf-yorkie](https://github.com/timdp/asdf-yorkie).

## Usage

Bootstrap your project's `.yorkie` folder:

```bash
yorkie
```

Add a hook:

```bash
echo 'npm test' >.yorkie/pre-commit
```

## Author

[Tim De Pauw](https://tmdpw.eu)

## License

MIT
