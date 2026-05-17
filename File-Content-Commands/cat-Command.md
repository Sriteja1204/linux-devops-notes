## Introduction

The `cat` command stands for **Concatenate**.  
It is used to display, combine, and create file contents in Linux.

---

## Learning Objective

By the end of this document, you will be able to:

- Display file contents using `cat`
- Combine multiple files
- Create files from terminal
- Use important `cat` options effectively

---

## Purpose

- View file contents
- Merge files
- Create text files quickly

---

## Syntax

```bash
cat [options] [file_name]
```

---

## Examples

### Display a file

```bash
cat notes.txt
```

### Display multiple files

```bash
cat file1.txt file2.txt
```

### Create a file

```bash
cat > sample.txt
```

---

## Option Explanation

| Option | Description |
|--------|-------------|
| `-n` | Display line numbers |
| `-b` | Number non-empty lines |
| `-s` | Remove repeated empty lines |
| `-E` | Show end of line characters |

---

## Real-Time Usage

- Viewing configuration files
- Checking logs quickly
- Combining text files

Example:

```bash
cat access.log
```

---

## Important Notes

- Suitable for small files
- Large files are better viewed using `less` or `more`
- Can overwrite files when used incorrectly with `>`
