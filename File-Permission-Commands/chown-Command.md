## Introduction

The `chown` command stands for **Change Ownership**.  
It is used to change the owner and group of files and directories.

---

## Learning Objective

By the end of this document, you will be able to:

- Change file ownership in Linux
- Modify user and group ownership
- Apply recursive ownership changes
- Manage permissions in multi-user environments

---

## Purpose

- Assign file ownership
- Manage group access
- Control resource ownership in Linux systems

---

## Syntax

```bash
chown [options] owner:group file_name
```

---

## Examples

### Change file owner

```bash
chown user1 notes.txt
```

### Change owner and group

```bash
chown user1:developers project.txt
```

### Change ownership recursively

```bash
chown -R user1:developers Project
```

---

## Option Explanation

| Option | Description |
|--------|-------------|
| `-R` | Change ownership recursively |
| `owner` | Specify new file owner |
| `owner:group` | Change both owner and group |
| `-v` | Display ownership changes |

---

## Real-Time Usage

- Managing web server files
- Assigning project ownership
- Configuring shared directories

Example:

```bash
chown www-data:www-data website/
```

---

## Important Notes

- Requires sudo privileges in many cases
- Incorrect ownership may restrict access
- Recursive changes affect all nested files
