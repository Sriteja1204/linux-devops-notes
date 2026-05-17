## Introduction

The `grep` command is used to search text patterns inside files.

---

## Learning Objective

By the end of this document, you will be able to:

- Search text patterns using `grep`
- Filter command outputs
- Perform case-insensitive searches
- Use pattern matching effectively

---

## Purpose

- Search specific text
- Filter large outputs
- Analyze logs and files

---

## Syntax

```bash
grep [options] "pattern" [file_name]
```

---

## Examples

### Search a word in file

```bash
grep "error" server.log
```

### Case-insensitive search

```bash
grep -i "warning" app.log
```

### Show line numbers

```bash
grep -n "root" users.txt
```

---

## Option Explanation

| Option | Description |
|--------|-------------|
| `-i` | Ignore case sensitivity |
| `-n` | Show line numbers |
| `-r` | Search recursively |
| `-v` | Show non-matching lines |
| `-c` | Count matching lines |

---

## Real-Time Usage

- Searching errors in logs
- Filtering command output
- Finding configuration entries

Example:

```bash
grep "failed" auth.log
```

---

## Important Notes

- Patterns are case-sensitive by default
- Supports regular expressions
- Powerful tool for system administrators
