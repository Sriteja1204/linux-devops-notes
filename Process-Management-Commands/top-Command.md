## Introduction

The `top` command provides a real-time view of running processes and system resource usage.

---

## Learning Objective

By the end of this document, you will be able to:

- Monitor live system processes
- Analyze CPU and memory usage
- Identify resource-intensive applications
- Use real-time monitoring tools effectively

---

## Purpose

- Monitor system performance
- Track CPU and memory usage
- Observe live process activity

---

## Syntax

```bash
top
```

---

## Examples

### Start top monitoring

```bash
top
```

### Display processes for specific user

```bash
top -u student
```

---

## Option Explanation

| Option | Description |
|--------|-------------|
| `-u` | Filter processes by user |
| `-d` | Set refresh interval |
| `-n` | Limit number of updates |
| `-p` | Monitor specific process ID |

---

## Real-Time Usage

- Monitoring server performance
- Detecting high CPU usage
- Troubleshooting slow systems

Example:

```bash
top -d 2
```

---

## Important Notes

- Press `q` to quit
- Updates dynamically in real time
- Useful for system administrators
