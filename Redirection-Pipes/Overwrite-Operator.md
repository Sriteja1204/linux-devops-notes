## Introduction

The overwrite operator (`>`) redirects command output to a file and replaces existing content.

---

## Learning Objective

By the end of this document, you will be able to:

- Redirect command output into files
- Overwrite file contents safely
- Store command results in text files
- Use output redirection effectively

---

## Purpose

- Save command output
- Create new files
- Replace existing file contents

---

## Syntax

```bash
command > file_name
```

---

## Examples

### Save output to file

```bash
ls > files.txt
```

### Store process information

```bash
ps -ef > process.txt
```

---

## Operator Explanation

| Operator | Description |
|----------|-------------|
| `>` | Redirect output and overwrite file |

---

## Real-Time Usage

- Saving logs
- Exporting command outputs
- Creating report files

Example:

```bash
df -h > disk-report.txt
```

---

## Important Notes

- Existing file content will be replaced
- Creates file if it does not exist
- Use carefully to avoid data loss
