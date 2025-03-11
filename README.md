# Text Editor Setup and Commands

Welcome to the ultimate guide for setting up and using popular text editors: **Neovim**, **Vim**, **NVChad**, and **Emacs**. This document provides direct download links as well as a collection of basic to advanced commands for both Vim and Emacs, with visual aids to help you master these editors.

---

## Download Links

- **Neovim:** [Download Neovim](https://neovim.io/)
- **Vim:** [Download Vim](https://www.vim.org/download.php)
- **NVChad:** [Download NVChad](https://nvchad.com/)
- **Emacs:** [Download Emacs](https://www.gnu.org/software/emacs/)

---

## Vim Commands

### Basic Commands
- **Enter Insert Mode:** Press `i`
- **Exit Insert Mode:** Press `Esc`
- **Save File:** `:w`
- **Quit Vim:** `:q`
- **Save and Quit:** `:wq`

### Intermediate Commands
- **Delete Line:** `dd`
- **Copy (Yank) Line:** `yy`
- **Paste:** `p`
- **Undo:** `u`
- **Redo:** `Ctrl+r`

### Advanced Commands
- **Global Replace:** `:%s/old/new/g`
- **Record a Macro:**  
  - Start recording: `qa` (record in register `a`)  
  - Stop recording: `q`
- **Visual Mode Selection:**  
  - Character mode: `v`  
  - Line mode: `V`  
  - Block mode: `Ctrl+v`

#### Vim Visual Aids
![Vim Modes](https://via.placeholder.com/600x300.png?text=Vim+Modes)
![Vim Cheat Sheet](https://via.placeholder.com/600x300.png?text=Vim+Cheat+Sheet)

---

## Emacs Commands

### Basic Commands
- **Open File:** `C-x C-f` (Press `Control + x`, then `Control + f`)
- **Save File:** `C-x C-s`
- **Exit Emacs:** `C-x C-c`

### Intermediate Commands
- **Cancel Command:** `C-g`
- **Execute Extended Command:** `M-x` (Press `Alt + x`)
- **Mark Text (Start Selection):** `C-space`
- **Cut (Kill Region):** `C-w`
- **Copy (Kill Ring Save):** `M-w`
- **Paste (Yank):** `C-y`

### Advanced Commands
- **Query Replace:** `M-%`
- **Evaluate Emacs Lisp Expression:** `C-x C-e`
- **Recording Macros:**  
  - Start recording: `F3` (or `C-x (` in some setups)  
  - End recording: `F4` (or `C-x )`)  
  - Replay macro: `F4` (or `C-x e`)

#### Emacs Visual Aids
![Emacs Modes](https://via.placeholder.com/600x300.png?text=Emacs+Modes)
![Emacs Cheat Sheet](https://via.placeholder.com/600x300.png?text=Emacs+Cheat+Sheet)

---

## Usage Guide

### Vim Usage Tips
- **Switching Modes:**  
  - Press `i` to enter Insert mode and start typing.  
  - Press `Esc` to return to Normal mode.
- **Navigation:**  
  - Use arrow keys or `h`, `j`, `k`, `l` in Normal mode.
- **Searching:**  
  - Press `/` to search forward or `?` to search backward.
- **Editing:**  
  - Use commands like `dd` to delete a line or `yy` to copy, then `p` to paste.

### Emacs Usage Tips
- **Opening Files:**  
  - Press `C-x C-f` to open a file and start editing.
- **Saving Work:**  
  - Press `C-x C-s` to save the current file.
- **Exiting:**  
  - Press `C-x C-c` to exit Emacs.
- **Command Execution:**  
  - Use `M-x` to run extended commands (e.g., to install packages or run scripts).

---

This README provides an overview to help you get started with these powerful text editors. Customize the content, commands, and images as needed to suit your workflow and preferences.
