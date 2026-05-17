## Introduction

The `df` command displays information about disk space usage on file systems.

---

## Learning Objective

By the end of this document, you will be able to:

- Monitor disk space usage
- Identify available storage
- Analyze mounted file systems
- Use human-readable disk reports

---

## Purpose

- Check storage availability
- Monitor disk utilization
- Analyze file system usage

---

## Syntax

```bash
df [options]
```

---

## Examples

### Display disk usage

```bash
df
```

### Display human-readable output

```bash
df -h
```

### Display file system type

```bash
df -T
```

---

## Option Explanation

| Option | Description |
|--------|-------------|
| `-h` | Human-readable format |
| `-T` | Display file system type |
| `-a` | Show all file systems |
| `-i` | Display inode information |

---

## Real-Time Usage

- Monitoring server storage
- Checking available disk space
- Troubleshooting storage issues

Example:

```bash
df -h
```

---

## Important Notes

- Useful for server maintenance
- Helps prevent disk overflow
- Human-readable format improves readability
