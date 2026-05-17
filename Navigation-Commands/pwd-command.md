# pwd Command

## Introduction

The `pwd` command stands for **Print Working Directory**.  
It displays the full path of the current directory you are working in.

---

## Purpose

- To identify the current directory location
- Helpful while navigating complex directory structures
- Commonly used in shell scripting and terminal operations

---

## Syntax

pwd

---

## Examples

**Display current directory**

```bash
pwd
```


**Output:**

```bash
/home/user/Documents
```

**Display physical directory path**

```bash
pwd -P
```

## Option	Description

`-L`    -	Prints logical working directory (default behavior)

`-P`	  - Prints physical directory without symbolic links


## Real-Time Usage

Checking current project folder before executing commands
Used in scripts to confirm execution location
Helpful during server administration and file management

**Example:**

```bash
cd /var/log

pwd
```

**Output:**

```bash
/var/log
```


## Important Notes

`pwd` does not change directories

It only displays the current path

Works in Linux, macOS, and Unix systems
