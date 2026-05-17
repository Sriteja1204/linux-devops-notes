## Introduction

The `ping` command is used to test connectivity between your system and another network device.

---

## Learning Objective

By the end of this document, you will be able to:

- Test network connectivity
- Measure response time between systems
- Diagnose basic network issues
- Use common `ping` command options

---

## Purpose

- Check internet connectivity
- Verify server availability
- Analyze network response times

---

## Syntax

```bash
ping [options] host_name
```

---

## Examples

### Ping a website

```bash
ping google.com
```

### Send limited ping requests

```bash
ping -c 4 google.com
```

---

## Option Explanation

| Option | Description |
|--------|-------------|
| `-c` | Specify number of packets |
| `-i` | Set interval between packets |
| `-s` | Define packet size |
| `-t` | Set TTL value |

---

## Real-Time Usage

- Checking internet connectivity
- Verifying server response
- Troubleshooting network issues

Example:

```bash
ping github.com
```

---

## Important Notes

- Press `Ctrl + C` to stop continuous ping
- Some servers block ping requests
- Requires network connectivity
