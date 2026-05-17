## Introduction

The `tail` command is used to display the last few lines of a file.

---

## Learning Objective

By the end of this document, you will be able to:

- View ending lines of files
- Monitor logs in real time
- Use live file tracking
- Apply common `tail` options

---

## Purpose

- Monitor log updates
- Read recent file content
- Debug applications

---

## Syntax

```bash
tail [options] [file_name]
```

---

## Examples

### Display last 10 lines

```bash
tail server.log
```

### Display last 5 lines

```bash
tail -n 5 server.log
```

### Monitor file updates live

```bash
tail -f server.log
```

---

## Option Explanation

| Option | Description |
|--------|-------------|
| `-n` | Specify number of lines |
| `-f` | Follow file updates live |
| `-c` | Display bytes |
| `-q` | Hide file headers |

---

## Real-Time Usage

- Monitoring server logs
- Watching live application output
- Tracking system updates

Example:

```bash
tail -f access.log
```

---

## Important Notes

- Default output is 10 lines
- `-f` is useful for live monitoring
- Commonly used in server administration
