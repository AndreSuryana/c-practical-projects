# 📄 textstat

A simple CLI tool that counts lines, words, and characters in a text file — similar to the Unix `wc` command — with extended options for analyzing text structure.

## 🛠 Features

- Line count
- Word count
- Character count
- Longest Line count
- Empty Lines count
- Optional output using flags
- Support for reading from `stdin`

## 🚀 Usage

Compile:

```sh
make
```

Read from file:

```sh
./textstat filename.txt
```

Read from standard input (e.g., piping):
```sh
cat filename.txt | ./textstat
```

With flags:

```sh
./textstat -lwc filename.txt   # Show lines, words, characters
./textstat -a filename.txt     # Show all stats
cat filename.txt | ./textstat -a
```

## 🧪 Example

Default output:

```sh
$ ./textstat filename.txt
Lines:      17
Words:      85
Characters: 521
```

With `-a` (all features):

```sh
$ ./textstat -a filename.txt
Lines:        17
Words:        85
Characters:   821
Longest Line: 45 characters
Empty Lines:  4
```

Piped input:

```sh
$ cat filename.txt | ./textstat -l
Lines: 17
```

## 🎯 Learning Focus

- File I/O in C (`fopen`, `fgets`, `fgetc`)
- Reading from `stdin` when no file is given
- Command-line argument parsing
- Flag-based feature toggles
- String and character manipulation
