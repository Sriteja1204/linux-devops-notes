## Introduction

The `cp` command stands for **Copy**.  
It is used to copy files and directories from one location to another.

---

## Purpose

- Duplicate files
- Backup important data
- Copy directories and project files

---

## Syntax

```bash
cp [source] [destination]
```

---

## Examples

### Copy a file

```bash
cp file.txt backup.txt
```

### Copy file to another directory

```bash
cp notes.txt Documents/
```

### Copy directories recursively

```bash
cp -r Project Backup/
```

---

## Option Explanation

| Option | Description |
|--------|-------------|
| `-r` | Copy directories recursively |
| `-i` | Ask before overwrite |
| `-v` | Show copied files |
| `-u` | Copy only updated files |

---

## Real-Time Usage

- Creating backups
- Duplicating project folders
- Moving files between systems

Example:

```bash
cp -r Website Website-Backup
```

---

## Important Notes

- Use `-r` for directories
- Existing files may be overwritten
- Verify destination paths carefully
