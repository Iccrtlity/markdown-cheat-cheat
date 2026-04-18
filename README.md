# Markdown README Cheat Sheet

![Markdown](https://img.shields.io/badge/markdown-reference-blue)
![Templates](https://img.shields.io/badge/templates-ready--to--use-green)
![Status](https://img.shields.io/badge/status-active-success)

A copy-paste reference for writing GitHub Markdown README files.

---

## Quick Start

- Templates → templates.md
- Use sections below as needed

---

## Basics

### Headings
```md
# H1
## H2
### H3
```

### Text
```md
*italic*
**bold**
~~strikethrough~~
```

### Lists
```md
- Item 1
- Item 2

1. First
2. Second
```

### Links & Images
```md
[Google](https://google.com)

![Alt text](image.png)
```

### Inline Code
```md
`code`
```

---

## Code Blocks

```bash
npm install
```

```js
console.log("Hello world");
```

---

## README Templates

### Minimal
```md
# Project Name

## Description
Short description.

## Installation
npm install

## Usage
Example

## License
MIT
```

---

### Standard Project
```md
# Project Name

## Description
What this project does.

## Features
- Fast
- Simple
- Lightweight

## Installation
git clone <repo>
cd project
npm install

## Usage
npm start

## License
MIT
```

---

## Advanced

### Collapsible Section
```md
<details>
<summary>Click to expand</summary>

Hidden content here.

</details>
```

### Table
```md
| Name | Age |
|------|-----|
| John | 25  |
```

### Badges
```md
![License](https://img.shields.io/badge/license-MIT-blue)
![Version](https://img.shields.io/badge/version-1.0.0-green)
```

### Task List
```md
- [x] Done
- [ ] Not done
```

---

## License

MIT