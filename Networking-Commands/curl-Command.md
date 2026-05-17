## Introduction

The `curl` command is used to transfer data between systems using URLs.

---

## Learning Objective

By the end of this document, you will be able to:

- Fetch data from web servers
- Send HTTP requests
- Download files using terminal
- Use API requests with `curl`

---

## Purpose

- Retrieve web content
- Test APIs
- Transfer files over networks

---

## Syntax

```bash
curl [options] URL
```

---

## Examples

### Fetch webpage content

```bash
curl https://example.com
```

### Download a file

```bash
curl -O https://example.com/file.zip
```

### Send GET request

```bash
curl -X GET https://api.example.com
```

---

## Option Explanation

| Option | Description |
|--------|-------------|
| `-O` | Save file with original name |
| `-X` | Specify request method |
| `-I` | Fetch headers only |
| `-d` | Send data in request |

---

## Real-Time Usage

- Testing REST APIs
- Downloading files
- Debugging web services

Example:

```bash
curl -I https://github.com
```

---

## Important Notes

- Supports multiple protocols
- Useful for API testing
- Requires internet connectivity
