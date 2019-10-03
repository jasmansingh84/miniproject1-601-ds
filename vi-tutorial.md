# VI(Visual Editor) Walkthrough

VI is a screen-oriented text editor originally created for the Unix operating system. Following are the commands for vi to get started.

**Open a file using vi**

Open your **Terminal** app & type `vi filename` file that you want to edit

(https://github.com/ds997/miniproject1-601-ds/blob/master/resources/Enable-vi-mode.png)


**Operating Modes**

There are two modes in **vi**, `command mode` & `Insert mode`

**1. Command mode**

In this mode commands are used to **move** around and edit text objects

| Key | Description |
| ------ | ----------- |
| <kbd>ESC</kbd> | returns you to `command mode` |

**2. Insert mode**

This is the mode you use to type or **insert** text into a buffer

| Key | Description | Reverse | Description |
| ------ | ----------- | ----------- | ----------- |
| <kbd>i</kbd> | insert text **before** the cursor. | <kbd>I</kbd> | insert text at the **start** of the line. |
| <kbd>a</kbd> | insert text **after** the cursor. | <kbd>A</kbd> | insert text at the **end** of the line. |
| <kbd>o</kbd> | new line **below** the current line. | <kbd>O</kbd> | new line **above** the current line. |

**Saving files**

* Saving changes

Go to `command mode` by <kbd>ESC</kbd> then type the commant `:wq`

| Command | Description |
| ------ | ----------- |
| `:wq` or `ZZ` | Save the contents & quit vi |

* Without saving changes

Go to `command mode` by <kbd>ESC</kbd> then type the commant `:wq`   

| Command | Description |
| ------ | ----------- |
| `:q!` | Quit vi without saving |


**Redo and Undo**

To Undo or reset multiple/single change or reset use the following commands:

| Command | Description |
| ------ | ----------- |
| `u` | undo changes |
| `:u` | undo one change |
| <kbd>CTRL</kbd>+<kbd>R</kbd> | redo change |
| `.` | repeat last change |

**Cut and paste**

To copy(Yank) or paste in vi use the following code:

| Command | Description |
| ------ | ----------- |
| `yy` | yank a line |
| `yw` | yank word |
| `y$` | yank to end of line |

## Contributors
Divyanshu Sachdeva - ds997
