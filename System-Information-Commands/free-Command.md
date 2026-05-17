## Introduction

The `free` command displays information about system memory usage including RAM and swap memory.

---

## Learning Objective

By the end of this document, you will be able to:

- Monitor memory usage
- Analyze RAM and swap utilization
- Display memory information in readable format
- Troubleshoot memory-related issues

---

## Purpose

- Check available memory
- Monitor RAM usage
- Analyze swap space usage

---

## Syntax

```bash
free [options]
```

---

## Examples

### Display memory usage

```bash
free
```

### Human-readable memory output

```bash
free -h
```

### Display memory continuously

```bash
free -s 2
```

---

## Option Explanation

| Option | Description |
|--------|-------------|
| `-h` | Human-readable output |
| `-m` | Display memory in MB |
| `-g` | Display memory in GB |
| `-s` | Refresh output after interval |

---

## Real-Time Usage

- Monitoring server memory
- Troubleshooting performance issues
- Checking swap memory utilization

Example:

```bash
free -h
```

---

## Important Notes

- Displays both RAM and swap usage
- Useful for system monitoring
- Often used with performance troubleshooting
