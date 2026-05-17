## Introduction

The `su` command stands for **Switch User**.  
It is used to switch from one user account to another in Linux.

---

## Learning Objective

By the end of this document, you will be able to:

- Switch between Linux user accounts
- Access root user sessions
- Execute commands as another user
- Manage multi-user environments effectively

---

## Purpose

- Change active user account
- Access administrative accounts
- Perform tasks under different users

---

## Syntax

```bash
su [username]
```

---

## Examples

### Switch to root user

```bash
su
```

### Switch to another user

```bash
su john
```

### Open login shell

```bash
su - john
```

---

## Option Explanation

| Option | Description |
|--------|-------------|
| `-` | Start full login shell |
| `-c` | Execute single command |
| `--help` | Display help information |

---

## Real-Time Usage

- Switching to administrator account
- Managing application users
- Performing user-specific tasks

Example:

```bash
su - postgres
```

---

## Important Notes

- Requires target user password
- Root access should be used carefully
- `su -` loads user environment variables
