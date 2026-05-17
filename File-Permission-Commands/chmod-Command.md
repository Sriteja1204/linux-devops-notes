## Introduction

`chmod` (short for **ch**ange **mode**) is a fundamental Linux/Unix command used to manage file and directory permissions  
It is used to modify file and directory permissions in Linux.

1. **Understanding the Three Target Audiences**

  Every file and directory has three distinct tiers of ownership:

  - User (`u`): The individual who owns the file.

  - Group (`g`): A collection of users who share access permissions.

  - Others (`o`): Anyone else with access to the system (the public).

  - All (`a`): A shorthand combination of all three (u, g, and o).


2. **Understanding the Three Basic Permissions**

Permissions define what an audience tier can actually do:

| Permission | Symbol | Numeric Value | What it means for a File | What it means for a Directory |
| :--- | :---: | :---: | :--- | :--- |
| **Read** | `r` | **4** | View the file's contents. | List the files inside the directory (`ls`). |
| **Write** | `w` | **2** | Modify or delete the file. | Create, delete, or rename files inside it. |
| **Execute** | `x` | **1** | Run the file (if it's a script/program). | Enter the directory (`cd` into it). |

3. **How to Use chmod**
There are two main ways to change permissions using chmod: **Absolute (Numeric) Mode** and **Symbolic Mode**.

**Method A:Absolute (Numeric) Mode**

This is the most common method. You use a 3-digit number where each digit represents a sum of the permissions for the **User**, **Group**, and **Others** (in that exact order).

To calculate a digit, you add up the values of the permissions you want to grant:

- `7` = Read + Write + Execute (4+2+1)

- `6` = Read + Write (4+2)

- `5` = Read + Execute (4+1)

- `4` = Read Only (4)

**Syntax**: chmod [three-digit-number] [filename]

**Common Examples:**

`chmod 777 file.txt` → **Full access to everyone**. (Anyone can read, write, and execute. Use with caution!)

`chmod 755 script.sh` → **Owner can do everything** (4+2+1). Group and Others can only read and execute (4+1). Common for scripts.

`chmod 644 document.pdf` → **Owner can read and write** (4+2). Group and Others can only read (4). Standard for text files and web pages.

**Method B: Symbolic Mode**

This method is perfect when you just want to add or remove a specific permission without recalculating the entire numeric score. It uses letters and operators:

**Operators:** + (add permission), - (remove permission), = (set exactly).

**Syntax:** chmod [audience][operator][permission] [filename]

**Common Examples:**

`chmod +x script.sh` → Makes the file **executable** for everyone.

`chmod u+w report.txt` → Adds **write** permission just for the user (owner).

`chmod g-w memo.txt` → Removes **write** permission from the group.

`chmod o-rwx private.txt` → Removes **all** permissions (read, write, execute) from others.

**Tip:** To check the currnet permissions of the file user `ls -l`. You will see a string like `-rw-r--r--`, where the first dash indicates a file, followed by three sets of `rwx` blocks for User, Group, and Others.

## Purpose

- Manage file access permissions
- Secure files and directories
- Control user access levels

---

## Syntax

```bash
chmod [options] permissions file_name
```

---

## Examples

### Give execute permission

```bash
chmod +x script.sh
```

### Set numeric permissions

```bash
chmod 755 script.sh
```

### Change directory permissions recursively

```bash
chmod -R 755 Project
```

---

## Option Explanation

| Option | Description |
|--------|-------------|
| `-R` | Change permissions recursively |
| `+x` | Add execute permission |
| `-w` | Remove write permission |
| `755` | Owner full access, others read and execute |
| `777` | Full permissions to everyone |

---

## Real-Time Usage

- Making shell scripts executable
- Securing server files
- Managing project access permissions

Example:

```bash
chmod 644 config.txt
```

---

## Important Notes

- Incorrect permissions may create security risks
- Use `777` carefully
- Recursive permission changes affect all files and folders
