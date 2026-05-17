## Introduction

The `systemctl` command is used to manage system services in Linux systems using systemd.

---

## Learning Objective

By the end of this document, you will be able to:

- Start and stop Linux services
- Check service status
- Enable and disable services
- Manage system services effectively

---

## Purpose

- Control system services
- Manage boot-time services
- Monitor service status

---

## Syntax

```bash
systemctl [command] [service_name]
```

---

## Examples

### Start a service

```bash
sudo systemctl start nginx
```

### Stop a service

```bash
sudo systemctl stop nginx
```

### Check service status

```bash
sudo systemctl status nginx
```

---

## Option Explanation

| Command | Description |
|---------|-------------|
| `start` | Start service |
| `stop` | Stop service |
| `restart` | Restart service |
| `status` | View service status |
| `enable` | Start service at boot |
| `disable` | Disable boot startup |

---

## Real-Time Usage

- Managing web servers
- Restarting applications
- Monitoring Linux services

Example:

```bash
sudo systemctl restart apache2
```

---

## Important Notes

- Requires sudo privileges in most cases
- Works on systemd-based Linux distributions
- Essential for server administration
