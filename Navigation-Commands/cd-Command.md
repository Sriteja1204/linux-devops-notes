# cd Command

## Introduction

The `cd` command stands for **Change Directory**.  
It is used to move from one directory to another in the terminal.

---

## Purpose

- Navigate between folders
- Access files and directories
- Manage system locations efficiently

---

## Syntax

```bash
cd [directory_path]
```

---

## Examples

Move to a specific directory
```bash
cd Documents
```

Move to parent directory
```bash
cd ..
```

Move to home directory
```bash
cd ~
```

Move to previous directory
```bash
cd -
```

## Option Explanation
       
`..`                        Parent directory 


`~`                         Home directory 


`-`                        	Previous directory 


`/`                         Root directory 


## Real-Time Usage
- Switching between project folders


- Accessing configuration directories

- Navigating server file systems

**Example:**

```bash
cd /etc/nginx
```

**Important Notes**

- Directory names are case-sensitive

- Use quotes for folder names containing spaces

**Example:**

```bash
cd "My Folder"
```

- Relative and absolute paths are supported
