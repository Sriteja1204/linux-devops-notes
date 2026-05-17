## Introduction

The `head` command is used to display the first few lines of a file.

---

## Learning Objective

By the end of this document, you will be able to:

- View beginning lines of files
- Limit output lines
- Analyze logs efficiently
- Use common `head` options

---

## Purpose

- Quickly preview files
- Read starting content
- Inspect logs and configurations

---

## Syntax

```bash
head [options] [file_name]
```

---

## Examples

### Display first 10 lines

```bash
head notes.txt
```

### Display first 5 lines

```bash
head -n 5 notes.txt
```

---

## Option Explanation

| Option | Description |
|--------|-------------|
| `-n` | Specify number of lines |
| `-c` | Display number of bytes |
| `-q` | Hide file name headers |

---

## Real-Time Usage

- Previewing large files
- Checking application logs
- Reading configuration starts

Example:

```bash
head -n 20 server.log
```

---

## Important Notes

- Default output is 10 lines
- Useful for large file inspection
- Faster than opening full files
