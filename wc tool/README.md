## Build Your Own wc Tool

The Unix wc (word count) command is used to count the number of lines, words, and bytes (or characters) in files

This option counts the number of lines in a file.
```bash
wc -l filename.txt
```

This option counts the number of words in a file.
```bash
wc -w filename.txt
```

This option counts the number of bytes in a file.
```bash
wc -c filename.txt
```

This option counts the number of characters in a file. This is useful for handling multibyte characters, which are common in languages other than English.
```bash
wc -m filename.txt
```