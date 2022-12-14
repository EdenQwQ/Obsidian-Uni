---
theme: catppuccin
width: 1500
controls: false
transition: convex
---

# What You'll Learn Today

- **Operator** and **motion**
- The magic **dot**
- A brief introduction to **macro**

---

# Miscellaneous

- ***Do not*** touch Capslock!!!
- Mapping capslock to escape
- Learn to read manuals and help tags
- Escape once in a while

---

# Basic Operator

Operator | Operation
---|---
`d` | delete
`c` | change 
`y` | yank
`p` | put
`~` | swap case
`gu` | lowercase
`gU` | uppercase
`<` | add indentation
`>` | remove indentation 
`=` | format code

---

# Basic Motion

`h j k l`

`0 ^ $$`

`w W b B e E`

`gg G`

`g{char}`

---

# Find Motion

`f F t T`

`; ,`

---

# Text Object

`a i`

`a i` + `w W s p ] [ ) ( b > < t } { B " '

---

# Combine Operator and Motion

`daw ciw yi" >G`

`d10G c5l yf; cT(`

---

# The Dot

`.`

Repeat paradigm: *Next; Repeat; Undo*

## **Tips**

- Make changes repeatable
- Don't repeat yourself
- Use short operators

---

# Macro

`q{a-z}`

`{num}@{a-z}`

`{num}@@`

`:reg {a-z}`

`q{A-Z}`

`:let @{a-z}=<C-r>{a-z}`