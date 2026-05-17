## Introduction

The `mkdir` command stands for **Make Directory**.  
It is used to create new directories in Linux.

---

## Purpose

- Create folders and subfolders
- Organize files systematically
- Prepare project structures

---

## Syntax

```bash
mkdir [directory_name]
```

---

## Examples

### Create a directory

```bash
mkdir Projects
```

### Create multiple directories

```bash
mkdir Docs Images Videos
```

### Create nested directories

```bash
mkdir -p Project/src/components
```

---

## Option Explanation

| Option | Description |
|--------|-------------|
| `-p` | Create parent directories if they do not exist |
| `-v` | Display message for each created directory |

---

## Real-Time Usage

- Creating project folders
- Organizing server directories
- Setting up application structures

Example:

```bash
mkdir -p WebApp/assets/images
```

---

## Important Notes

- Directory names are case-sensitive
- Existing directory names cannot be reused
- Use `-p` for nested structures
