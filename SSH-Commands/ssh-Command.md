## Introduction

The `ssh` command is used to securely connect to remote Linux systems over a network.

---

## Learning Objective

By the end of this document, you will be able to:

- Connect to remote systems using SSH
- Understand secure remote access
- Execute commands on remote servers
- Use common SSH command options

---

## Purpose

- Secure remote login
- Remote server administration
- Execute commands remotely

---

## Syntax

```bash
ssh [options] username@hostname
```

---

## Examples

### Connect to remote server

```bash
ssh user@192.168.1.10
```

### Connect using specific port

```bash
ssh -p 2222 user@server.com
```

---

## Option Explanation

| Option | Description |
|--------|-------------|
| `-p` | Specify custom port |
| `-i` | Use identity/private key file |
| `-v` | Enable verbose mode |
| `-X` | Enable X11 forwarding |

---

## Real-Time Usage

- Accessing cloud servers
- Managing Linux servers remotely
- Secure remote troubleshooting

Example:

```bash
ssh admin@server.com
```

---

## Important Notes

- Requires SSH server on remote system
- Secure alternative to Telnet
- Internet or network connectivity required
