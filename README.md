# RegexRenamer
Performs bulk renaming of files using regexes from the command line.

## Compiling

Use csc (CSharp compiler command line). You can do this by opening a Developer Command Prompt if you have VS installed.

```
csc -recurse:src\*.cs -out:rxn.exe
```

## Usage

```
RXN.exe - performs regular expression renaming of files.
Usage: rxn <dir> <pattern> <replacement> [/pcwr]

 p   Preview changes
 c   Case sensitive
 w   Ignore pattern whitespace
 r   Right-to-left
```
