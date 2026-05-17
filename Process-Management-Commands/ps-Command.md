## Introduction

The `ps` command is used to display information about active processes running on a Linux system.

---

## Learning Objective

By the end of this document, you will be able to:

- View running processes
- Analyze process details
- Filter process information
- Use process monitoring in Linux administration

---

## Purpose

- Display active processes
- Monitor system tasks
- Inspect process details

---

## Syntax

```bash
ps [options]
```

---

## Examples

### Display current shell processes

```bash
ps
```

### Display all running processes

```bash
ps -aux
```

### Display process tree

```bash
ps -ef
```

---

## Option Explanation

| Option | Description |
|--------|-------------|
| `-a` | Show processes for all users |
| `-u` | Display user-oriented format |
| `-x` | Show processes without terminal |
| `-e` | Display all processes |
| `-f` | Full process listing |

---

## Real-Time Usage

- Checking running applications
- Finding process IDs
- Monitoring server activities

Example:

```bash
ps -ef | grep nginx
```

---

## Important Notes

- Useful for process troubleshooting
- Often combined with `grep`
- Displays snapshot of current processes
