## Introduction

The `mv` command stands for **Move**.  
It is used to move or rename files and directories.

---

## Purpose

- Rename files
- Move files between directories
- Organize project structures

---

## Syntax

```bash
mv [source] [destination]
```

---

## Examples

### Rename a file

```bash
mv old.txt new.txt
```

### Move file to another directory

```bash
mv notes.txt Documents/
```

### Rename a directory

```bash
mv OldFolder NewFolder
```

---

## Option Explanation

| Option | Description |
|--------|-------------|
| `-i` | Ask before overwrite |
| `-v` | Display moved files |
| `-n` | Prevent overwrite |

---

## Real-Time Usage

- Renaming project folders
- Organizing documents
- Moving logs and backups

Example:

```bash
mv app.log Logs/
```

---

## Important Notes

- Files may be overwritten if names match
- Moving across drives may take longer
- Works for both files and directories
