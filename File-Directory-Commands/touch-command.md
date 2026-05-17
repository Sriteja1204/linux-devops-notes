## Introduction

The `touch` command is used to create empty files and update file timestamps.

---

## Purpose

- Create new empty files
- Update modification timestamps
- Quickly prepare configuration or script files

---

## Syntax

```bash
touch [file_name]
```

---

## Examples

### Create a file

```bash
touch notes.txt
```

### Create multiple files

```bash
touch file1.txt file2.txt file3.txt
```

### Update file timestamp

```bash
touch existing.txt
```

---

## Option Explanation

| Option | Description |
|--------|-------------|
| `-a` | Change access time only |
| `-m` | Change modification time only |
| `-c` | Do not create file if it does not exist |

---

## Real-Time Usage

- Creating configuration files
- Initializing log files
- Preparing scripts

Example:

```bash
touch app.js
```

---

## Important Notes

- Existing files are not overwritten
- Creates empty files only
- Supports multiple file creation at once
