# How to Insert a Table to a Markdown File

***Last edit: 16:59:59 2/9/2019***

I have inserted a lot of tables recently in Markdown, so I might as well write an article about how to do that.

----

Everything is easy in Markdown, including adding a table. To create a table, all you need is these three characters:

    "-", "|", ":".

Let's create a table of the test results of some students with these lines.

    | Name | Number | Score | Rank |
    | :---- | ----: | :----: | ---- |
    Jack Dawson | 1 | 23 | 4
    Rose Tyler | 2 | 89 | 2
    | Li Lei | 3 | 59 | 3 |
    Han Meimei | 4 | 93 | 1

Result:

| Name | Number | Score | Rank |
| :---- | ----: | :----: | ---- |
Jack Dawson | 1 | 23 | 4
Rose Tyler | 2 | 89 | 2
| Li Lei | 3 | 59 | 3 |
Han Meimei | 4 | 93 | 1

These lines below are basically self-explanatory. But here are some points you should be aware of:

- A table can either have boarders or not. They both work.
- Even though a markdown file may seem different on different platforms or programs when previewing, these headers are usually bold.
- The colon character determines the adjustment mode of this column. ":----" or "----"(no colon) stands for "left-adjusted", ":----:" stands for "central-adjusted", "----:" stands for "right-adjusted".

----

## **[⇦ Previous: A Journey to macOS](https://angelohyang.github.io/Blog/Jan.%202019/A%20Journey%20to%20macOS)**

## **[⇨ Next: Finding Divisors - Algorithm Simplification](https://angelohyang.github.io/Blog/Feb.%202019/Finding%20Divisors%20-%20Algorithm%20Simplification)**

## **[🏡 Back To Home Page](https://angelohyang.github.io/Blog/)**