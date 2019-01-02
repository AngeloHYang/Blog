# Adding Links in Markdown

***Last edit: 12/17/2018 12:56:56 PM***

As a markup language, Markdown is capable of adding links into it. There are mainly three ways to add links in a md file.

## 1. Adding links in a line

    [name of a link](address of the link "With a Title")

This is usually used when you want to add links in a line with a name or other things instead of the link itself.

I used this to add link as follows. [Markdown 插入链接](https://www.jianshu.com/p/ab539e9a7955 "Markdown 插入链接 - 来自简书")

Can you add links to photos? Well, don't forget the way to add photos in Markdown is

    ![you can add a name here(optional)](put your link here)

[![简书logo](https://cdn2.jianshu.io/assets/web/nav-logo-4c7bbafe27adc892f3046e6978459bac.png)](https://www.jianshu.com/p/ab539e9a7955 "Markdown 插入链接 - 来自简书")

The answer is yes.

## 2. Reference

We could also name a link, so that when we need to add this link multiple times, instead of adding the link as what's above, we could simply call it's name.

This is how you call it:

    [words to display][name of the link]

This is how you modify it:

    [name of the link]: put the link here

For example:

[what ever]: https://www.jianshu.com/p/ab539e9a7955

This is the website I'd like to call [Markdown 插入链接][what ever]

You can call the link first and modify it later or the other way around. They both work.

The name that you give to the link consists of spaces, numbers, and letters. However, uppercase letters and lowercase letters are treated the same.

## 3. Show the link as what it is

Sometimes the easiest way to tell people it is a link and you can click on it is putting up a link as what it is. To do that, you should write:

    <the link itself>

For example, you could click this link <https://www.github.com>.

*Thanks to [Everett_Lao](https://www.jianshu.com/u/5f550fe15c01).*

##  **[Back To Home Page](https://angelohyang.github.io/Blog/)**