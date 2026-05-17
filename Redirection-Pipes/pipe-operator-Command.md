## Introduction

The pipe operator (`|`) is used to send the output of one command as input to another command.

---

## Learning Objective

By the end of this document, you will be able to:

- Understand command piping in Linux
- Combine multiple commands efficiently
- Filter command outputs
- Build powerful command-line workflows

---

## Purpose

- Connect multiple commands
- Process command outputs
- Improve command-line productivity

---

## Syntax

```bash
command1 | command2
```

---

## Examples

### Filter files using pipe

```bash
ls -l | grep ".txt"
```

### Count files

```bash
ls | wc -l
```

### Display running process

```bash
ps -ef | grep nginx
```

---

## Operator Explanation

| Operator | Description |
|----------|-------------|
| `|` | Pass output of one command as input to another |

---

## Real-Time Usage

- Filtering logs
- Searching running processes
- Processing command outputs

Example:

```bash
cat access.log | grep "ERROR"
```

---

## Important Notes

- Multiple pipes can be chained together
- Useful in automation scripts
- Improves command flexibility
