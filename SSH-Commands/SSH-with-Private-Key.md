## Introduction

SSH private key authentication allows secure login to remote systems without using passwords.

---

## Learning Objective

By the end of this document, you will be able to:

- Connect using SSH private keys
- Configure secure remote authentication
- Use key-based login methods
- Manage SSH identity files effectively

---

## Purpose

- Enable secure authentication
- Avoid password-based login
- Improve server security

---

## Syntax

```bash
ssh -i private_key username@hostname
```

---

## Examples

### Connect using private key

```bash
ssh -i ~/.ssh/id_rsa user@server.com
```

### Connect using custom key

```bash
ssh -i mykey.pem ubuntu@aws-server.com
```

---

## Option Explanation

| Option | Description |
|--------|-------------|
| `-i` | Specify private key file |
| `-p` | Specify custom SSH port |
| `-v` | Enable verbose output |

---

## Real-Time Usage

- Accessing AWS EC2 instances
- Connecting to cloud servers
- Secure DevOps automation

Example:

```bash
ssh -i production.pem admin@192.168.1.20
```

---

## Important Notes

- Private keys must remain confidential
- Key permissions should be restricted

Example:

```bash
chmod 600 private_key.pem
```

- Incorrect permissions may block SSH access
