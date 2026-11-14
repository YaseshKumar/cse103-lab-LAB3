In this exercise you will write professional project documentation using Markdown — the lightweight markup

language used throughout GitHub, documentation sites, and developer blogs. You will create a comprehensive README.md that includes headings, formatted lists, code blocks, links, a data table, and badges. You will also write a Markdown syntax reference guide. Well-structured documentation is a strong indicator of professionalism in open-source and industry work.

Step 1: Learn Core Markdown Syntax

Navigate to your repo: cd ~/cse103_lab/LAB3/my_first_repo

Create a practice file: nano MARKDOWN_GUIDE.md

Enter and study each example below, then save:

# Heading 1 (largest)

## Heading 2

### Heading 3

Bold text Italic text Strikethrough

Unordered list:

- Item A

- Item B

- Nested item B1 (indent with 2 spaces)

Ordered list:

1. First step

2. Second step

Inline code: print("Hello")

Fenced code block (use language name for syntax highlighting):

```python

def greet(name):

return f"Hello, {name}!"```

Hyperlink: [GitHub](https://github.com)

Table:

| Column 1 | Column 2 | Column 3 |

|----------|:--------:|----------:|

| Left | Centre | Right |

Blockquote:

> An important note or reference goes here.

Horizontal divider:

---

Step 2: Write a Professional README.md

Replace your basic README.md: nano README.md

Enter the following template, customising every [placeholder]:

# CSE103 Lab — LAB 3: GitHub Collaboration & API Interaction

![Last Commit](https://img.shields.io/github/last-commit/[username]/cse103-lab-LAB3)

![Language](https://img.shields.io/badge/language-Python-blue)

![Status](https://img.shields.io/badge/status-active-brightgreen)

## Overview

This repository contains lab work for LAB 3 of the

Computer Fundamentals & Career Pathways (CSE103) course at

K.R. Mangalam University, Gurugram.

## Repository Structure

```

cse103-lab-LAB3/

+-- README.md # Project documentation (this file)

+-- CHANGELOG.md # Version history

+-- main.py # Primary Python script

+-- .gitignore # Files excluded from Git tracking

```

## Skills Demonstrated

| Skill | Status |

|----------------------|-------------|

| Git initialisation | Completed |

| Meaningful commits | Completed |

| Remote push / pull | Completed |

| Markdown docs | Completed |

| API interaction | Completed |

## How to Run

```bash

git clone https://github.com/[username]/cse103-lab-LAB3.git

cd cse103-lab-LAB3

python3 main.py

```

## Key Learning Outcomes

- Configured Git identity and initialised local repositories

- Created atomic commits with Conventional Commit messages

- Pushed and pulled changes with a GitHub remote

- Authored structured Markdown documentation

## References

- [Pro Git Book](https://git-scm.com/book/en/v2)

- [GitHub Skills](https://skills.github.com/)

- [Markdown Guide](https://www.markdownguide.org/)
## Description
CSE103 lab repository — LAB 3.


Updated README from GitHub.
