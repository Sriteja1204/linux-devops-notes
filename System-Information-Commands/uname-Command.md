## Introduction

The `uname` command is used to display system information such as operating system, kernel version, and architecture.

---

## Learning Objective

By the end of this document, you will be able to:

- View Linux system details
- Identify kernel information
- Check system architecture
- Use `uname` command options effectively

---

## Purpose

- Retrieve operating system information
- Display kernel version
- Identify hardware architecture

---

## Syntax

```bash
uname [options]
```

---

## Examples

### Display kernel name

```bash
uname
```

### Display all system information

```bash
uname -a
```

### Display kernel version

```bash
uname -r
```

---

## Option Explanation

| Option | Description |
|--------|-------------|
| `-a` | Display all system information |
| `-r` | Show kernel release |
| `-m` | Display machine hardware name |
| `-s` | Show kernel name |

---

## Real-Time Usage

- Checking Linux kernel version
- Identifying server architecture
- Troubleshooting compatibility issues

Example:

```bash
uname -a
```

---

## Important Notes

- Helpful for system diagnostics
- Commonly used in shell scripts
- Available in most Unix-like systems
