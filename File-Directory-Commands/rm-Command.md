## Introduction

The `rm` command stands for **Remove**.  
It is used to delete files and directories.

---

## Purpose

- Delete unwanted files
- Remove directories
- Clean temporary data

---

## Syntax

```bash
rm [file_name]
```

---

## Examples

### Remove a file

```bash
rm notes.txt
```

### Remove multiple files

```bash
rm file1.txt file2.txt
```

### Remove a directory recursively

```bash
rm -r Project
```

---

## Option Explanation

| Option | Description |
|--------|-------------|
| `-r` | Remove directories recursively |
| `-f` | Force delete |
| `-i` | Ask before deletion |
| `-v` | Show deleted files |

---

## Real-Time Usage

- Cleaning old logs
- Removing temporary files
- Deleting project directories

Example:

```bash
rm -rf cache/
```

---

## Important Notes

- Deleted files usually cannot be recovered
- Use `rm -rf` carefully
- Double-check file paths before deletion
