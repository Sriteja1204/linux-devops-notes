# Append Operator.md## Introduction

The append operator (`>>`) redirects command output to a file without removing existing content.

---

## Learning Objective

By the end of this document, you will be able to:

- Append output to existing files
- Preserve existing file data
- Maintain logs using terminal commands
- Use append redirection safely

---

## Purpose

- Add content to files
- Maintain logs
- Store command history incrementally

---

## Syntax

```bash
command >> file_name
```

---

## Examples

### Append output to file

```bash
date >> logs.txt
```

### Append disk usage information

```bash
df -h >> system-report.txt
```

---

## Operator Explanation

| Operator | Description |
|----------|-------------|
| `>>` | Redirect output and append to file |

---

## Real-Time Usage

- Updating log files
- Storing monitoring reports
- Maintaining command records

Example:

```bash
echo "Backup completed" >> backup.log
```

---

## Important Notes

- Existing content remains unchanged
- Creates file if it does not exist
- Useful for logging and monitoring
