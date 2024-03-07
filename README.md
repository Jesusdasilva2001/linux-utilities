# Custom Linux Utils
## `ls` - List Directory Contents

- `./ls -a`: List all contents, including hidden files
- `./ls -H`: List contents with sizes in a human-readable format

## `cat` - Concatenate and Display Files

`./cat /path/to/file`: Display the content of a specified file

## `ln` - Create Links

- `./ln /path/to/target /path/to/linkname`: Create a hard link to a target file

- `./ln -s /path/to/target /path/to/symlink: Create a symbolic link to a target file

## `grep` - Pattern Search in Text

- `./grep "pattern" /path/to/file`: Search for a pattern within a specified file

mathematica

## `wc` - Word, Line, Character, and Byte Count
`./wc /path/to/file`: Count lines, words, characters, and bytes in a file

## Bonus:
- `./cat example.txt | grep 'some-pattern'`: This command concatenates and displays the content of `example.txt`, piping it through `grep` to filter and display lines that match 'some-pattern'.
