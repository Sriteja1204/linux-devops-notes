## Introduction

The `kill` command is used to terminate processes in Linux.

---

## Learning Objective

By the end of this document, you will be able to:

- Stop unwanted processes
- Use process IDs effectively
- Apply different kill signals
- Manage system processes safely

---

## Purpose

- Terminate running processes
- Stop unresponsive applications
- Control process execution

---

## Syntax

```bash
kill [signal] process_id
```

---

## Examples

### Kill a process

```bash
kill 1234
```

### Force kill a process

```bash
kill -9 1234
```

---

## Option Explanation

| Option | Description |
|--------|-------------|
| `-9` | Force terminate process |
| `-15` | Graceful termination |
| `-l` | List available signals |

---

## Real-Time Usage

- Stopping frozen applications
- Managing background jobs
- Troubleshooting system issues

Example:

```bash
kill -9 4567
```

---

## Important Notes

- Requires correct process ID
- Force kill should be used carefully
- Incorrect termination may affect services
