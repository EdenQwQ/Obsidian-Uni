---
theme: catppuccin
width: 1500
controls: false
transition: convex
---

# What You'll Learn Today

- **History** of vim
- Basic knowledge of **editing with vim**
- Some basic **notations** and **concepts** you should understand
- Basic understanding of **modes** in vim

---

# **What** Is Vim?

> *Vi* *Im*proved

1969 Ed -> 1976 Ex -> 1977 Vi -> 1991 Vim -> 2014 Neovim

---

# **Why** Vim?

- *Fast*: Edit text at the speed of thought
- *Minimal*: Small disk and memory usage
- *Customizable*: Everything is under control
- *Extensible*: Built-in plugin system

---

## Why Neovim?

- Superset of vim
- Even more customizable
- Even more extensible (with lua)
- More built-in features for efficiency

---

# **How** To Learn Vim?

- `:h vimtutor`
- *Practical Vim*
- Practice! Practice! Practice!
- No need to fear!

---

# **When** To Learn Vim?

***Never too late to learn.***

> 学习vim唯一的坏处是，你会后悔没有早点学vim.
> 
> ——忘记是谁说的了

---

# **Philosophy** Of Vim

- Keyboard is better than mouse
- Reading takes longer than writing
- Simple is better than complex

---

# Notation Declaration

Notation | Meaning
---|---
`x` | Press `x` once
`dw` | In sequence, press `d`, then `w`
`dap` | In sequence, press `d`, `a`, and `p`

---

Notation | Meaning 
--- | ---
`<C-n>` | Press `<Ctrl>` and `n` at the same time
`<C-w><C-v>` | Press `<Ctrl>` and `w` at the same time, then `<Ctrl>` and `n`

---

Notation | Meaning 
---|---
`f{char}` | Press `f`, followed by any other character
`'{a-z}` | Press `'`, followed by lowercase letter
`q{a-zA-Z}` | Press `q`, followed by letter
`c{motion}` | Press `c`, followed by any motion command
`<C-r>{register}` | Press `<C-r>`, followed by the address of a register.

---

## Special Keys

`<Esc> <CR> <Ctrl> <Tab> <Shift>`

`<S-Tab>`

`<Up> <Down> <Left> <Right>`

`␣`

---

# Basic **Concepts**

- Edit and change
- Buffer
- Modes
	- Normal mode
	- Insert mode
	- Visual mode
	- Command mode
	- Search mode
	- Operator pending mode
	- ~~Terminal mode~~
- Register 
- Command and script

---

# How to **Quit**!

`:q :quit` quit directly

`:wq :write | quit` save and quit

`:q!` force quit

---

# Changing **Modes**

`i I a A o O` Normal -> Insert 

`v V <C-v>` Normal -> Visual 

`:` Normal -> Command 

`/ ?` Normal -> Search 

`<Esc>` Others -> Normal

---

# Start with **Operators**

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