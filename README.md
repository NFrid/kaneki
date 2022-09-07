# Kaneki Ken number generator

An extremely useful number generator script written in Python.

## Usage

You can use `kaneki -h` to see its options.

When you use it without any options, it will generate a number sequence
delimited by line breaks that consists of Kaneki Ken himself subtracting 7
starting from 1000 and going down to 0 or less. These are
`993, 986, 979, ..., 13, 6, -1`.

You can pass `-v` or `--verbose` option to print full expressions instead so
you'll get something like this:

```
1000 - 7 = 993
993 - 7 = 986
986 - 7 = 979
...
13 - 7 = 6
6 - 7 = -1
```

You can also specify:
- a number to start with by passing it as an argument: `kaneki 100`,
- a number to subtract by passing `-s` or `--subtract` option followed by a
  number: `kaneki -s 3`,
- a number to stop at by passing `-l` or `--limit` option followed by a number:
  `kaneki -l 100`.
