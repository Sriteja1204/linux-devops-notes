## Introduction

The `ls` command is used to list files and directories in Linux and Unix systems.

---

## Purpose

- View directory contents
- Identify files and folders
- Display permissions, hidden files, and detailed information

---

## Syntax

```bash
ls [options] [directory]
```

---

## Example

**List files in current directory**

```bash
ls
```

**Detailed file listing**

```bash
</bash>
ls -l
```

**Show hidden files**

```bash
</bash>
ls -a
```

**Human-readable file sizes**

```bash
<bash>
ls -lh
```

## Option Explanation

`-l` 	Long listing format

`-a`	Show hidden files

`-h`	Human-readable sizes

`-t`	Sort by modification time

`-r`	Reverse order

`-R`	Recursive listing


**Real-Time Usage**

- Viewing project files
- Checking log directories
- Inspecting server contents

**Example:**
```bash
</bash>
ls -lh /var/log
```

**Important Notes**

- Hidden files start with .
- Combine multiple options together

**Example:**

```bash
</bash>
ls -lah
```

- `ls` output colors may vary depending on terminal configuration
