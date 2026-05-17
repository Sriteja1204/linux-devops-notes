## Introduction

The `sudo` command stands for **Super User Do**.  
It allows authorized users to execute commands with administrative privileges.

---

## Learning Objective

By the end of this document, you will be able to:

- Execute commands with elevated privileges
- Understand administrative access in Linux
- Use `sudo` securely
- Perform system-level operations safely

---

## Purpose

- Run administrative commands
- Install and manage software
- Modify protected system files

---

## Syntax

```bash
sudo [command]
```

---

## Examples

### Update package list

```bash
sudo apt update
```

### Edit protected file

```bash
sudo nano /etc/hosts
```

---

## Option Explanation

| Option | Description |
|--------|-------------|
| `-u` | Run command as another user |
| `-k` | Reset cached password |
| `-l` | List allowed commands |
| `-v` | Refresh sudo session |

---

## Real-Time Usage

- Installing software packages
- Restarting services
- Managing system configurations

Example:

```bash
sudo systemctl restart nginx
```

---

## Important Notes

- Requires user authorization
- Incorrect commands may affect system stability
- Use administrative access carefully
