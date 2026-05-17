## Introduction

The `find` command is used to search for files and directories in Linux systems.

---

## Purpose

- Locate files quickly
- Search directories recursively
- Filter files using conditions

---

## Syntax

```bash
find [path] [options] [expression]
```

---

## Examples

### Find a file by name

```bash
find . -name "notes.txt"
```

### Find all `.log` files

```bash
find /var/log -name "*.log"
```

### Find directories only

```bash
find . -type d
```

---

## Option Explanation

| Option | Description |
|--------|-------------|
| `-name` | Search by file name |
| `-type f` | Search files only |
| `-type d` | Search directories only |
| `-size` | Search by file size |
| `-mtime` | Search by modification time |

---

## Real-Time Usage

- Searching configuration files
- Finding logs in servers
- Locating project resources

Example:

```bash
find . -name "*.js"
```

---

## Important Notes

- Searches recursively by default
- Wildcards require quotes
- Can consume time in large directories
