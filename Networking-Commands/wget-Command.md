## Introduction

The `wget` command is used to download files from the internet.

---

## Learning Objective

By the end of this document, you will be able to:

- Download files using terminal
- Resume interrupted downloads
- Download files recursively
- Use `wget` efficiently in Linux

---

## Purpose

- Download web files
- Retrieve software packages
- Backup online resources

---

## Syntax

```bash
wget [options] URL
```

---

## Examples

### Download a file

```bash
wget https://example.com/file.zip
```

### Resume interrupted download

```bash
wget -c https://example.com/file.zip
```

### Download files in background

```bash
wget -b https://example.com/file.zip
```

---

## Option Explanation

| Option | Description |
|--------|-------------|
| `-c` | Resume interrupted download |
| `-b` | Download in background |
| `-O` | Save with different file name |
| `-r` | Recursive download |

---

## Real-Time Usage

- Downloading software packages
- Backing up websites
- Retrieving datasets from servers

Example:

```bash
wget https://releases.ubuntu.com/file.iso
```

---

## Important Notes

- Works without graphical browser
- Supports background downloading
- Useful for server environments
