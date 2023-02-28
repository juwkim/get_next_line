<h1 align="center">
	📖 get_next_line
</h1>

<p align="center">
	<b><i>Reading a line from a fd is way too tedious</i></b><br>
</p>

<p align="center">
	<img alt="GitHub code size in bytes" src="https://img.shields.io/github/languages/code-size/juwkim/get_next_line?color=lightblue" />
	<img alt="Code language count" src="https://img.shields.io/github/languages/count/juwkim/get_next_line?color=yellow" />
	<img alt="GitHub top language" src="https://img.shields.io/github/languages/top/juwkim/get_next_line?color=blue" />
	<img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/juwkim/get_next_line?color=green" />
</p>
<h3 align="center">
	<a href="#-about-the-project">About</a>
	<span> · </span>
	<a href="#%EF%B8%8F-usage">Usage</a>
</h3>

---

## 💡 About the project

> _This project is about programming a function that returns a line read from a file descriptor._

    This project will not only allow you to add a very convenient function to your collection,
    but it will also make you learn a highly interesting new concept in C programming: static variables.
    
    You will understand how files are opened, read and closed in an OS,
    and how they are interpreted by a programming language for further analysis.
    This task is crucial to understand for a future programmer since much of the time is based
    on manipulating files for data management and persistence.
    This project consists of coding a function that returns one line at a time from a text file.

For more detailed information, look at the [**subject of this project**](https://github.com/juwkim/42cursus/blob/main/Subject%20PDFs/01_get_next_line.pdf).


## 🛠️ Usage

### Requirements

The function is written in C language and thus needs the **C compiler** and some standard **C libraries** to run.

### Instructions

- Pull files ↙️
```shell
$ git clone https://github.com/juwkim/get_next_line
```

- To compile ↙️
```shell
cc -Wall -Werror -Wextra -D BUFFER_SIZE=<size> get_next_line.c get_next_line_utils.c "main.c"
```

- To use get_next_line in your code ↙️

```C
#include "get_next_line.h"
```
