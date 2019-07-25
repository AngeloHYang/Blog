# To Create a Simplified Version of *`ls`*

***Last edit: 22:53:01 7/25/2019***

So, I wrote a simplified version of the famous command `ls` in C++.

---

## Introduction

> `ls`: List information about the FILEs.

If you haven't heard about `ls` before, which you shouldn't, here's what it looks like.

![Ls_command_result.png](https://upload.wikimedia.org/wikipedia/commons/c/cc/Ls_command_result.png)

As for mine, take a look.

![my ls preview](my_ls_preview.png)

## Functions

To write a program like that in C++, here are some functions I find helpful.

Functions | Usage | Notes
---- | ---- | ----
`DIR * opendir(const char * name)` | To open directory `name` and return a `directory stream` | Similar to `fopen()`
`struct dirent * readdir(DIR * dir)` | To return the `entry` (in a struct dirent pointer to) of the next directory of the stream | Similar to `fread()`
`int closedir(DIR *dir)` | To close the `directory stream` | Similar to `fclose()`
`int stat(const char *path, struct stat *buf)` | Return information about a file
`getpwuid`

---

## References

1. [Ls_command_result.png](https://commons.wikimedia.org/wiki/File:Ls_command_result.png), Jppizarro. Retrieved in July, 25, 2019.

---

## **[⇦ Previous: Binary Search](https://angelohyang.github.io/Blog/Feb.%202019/Binary%20Search)**

## **[🏡 Back to Home Page](https://angelohyang.github.io/Blog/)**
