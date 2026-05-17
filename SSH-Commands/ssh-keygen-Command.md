## Introduction

The `ssh-keygen` command is used to generate SSH public and private key pairs.

---

## Learning Objective

By the end of this document, you will be able to:

- Generate SSH key pairs
- Understand public and private keys
- Secure remote authentication
- Configure passwordless SSH login

---

## Purpose

- Create SSH authentication keys
- Improve remote login security
- Enable passwordless authentication

---

## Syntax

```bash
ssh-keygen [options]
```

---

## Examples

### Generate default SSH key

```bash
ssh-keygen
```

### Generate RSA key with custom bits

```bash
ssh-keygen -t rsa -b 4096
```

---

## Option Explanation

| Option | Description |
|--------|-------------|
| `-t` | Specify key type |
| `-b` | Define key size |
| `-f` | Specify output file |
| `-C` | Add key comment |

---

## Real-Time Usage

- Configuring GitHub SSH authentication
- Securing cloud server access
- Automating remote connections

Example:

```bash
ssh-keygen -t ed25519
```

---

## Important Notes

- Keep private keys secure
- Never share private key files
- Public keys can be shared safely
