# Things About HTML, Markdown, CSS, and JavaScript

***Last edit: 14:49:33 1/12/2019***

When it comes to creating a web page, the word HTML occurs constantly. As I study further and further, words like Markdown and CSS become familiar to me. Although I have never written anything in HTML, JavaScript, or CSS directly before, I believe it is of great use to **gather some information** about them.

----

## Summary

### 1. HTML

HTML stands for "Hypertext Markup Language". According to Wikipedia,

> HTML is the standard markup language for creating web pages and web applications.

Before we go and explain the line above, here are some questions we should focus on first:

- What is the meaning of "Markup Language"?

  Imagine an actor staring at a script. There are words that tell him what he should say in the next play, we call them "dialogs", and there are words that tell him how he should say those dialogs, in what kind of emotion he should be when playing it, let's call it "instruction text".
  
  In the world of computers, when writing a document, there are "dialogs" that determine what contents will be displayed. There are also "instruction text" that determines how these contents in the document shall be displayed, such as the size of a word or in which place paragraph a photo is to be put. We call "instruction texts" in computer text processing "tags".

  According to Wikipedia:

  > In computer text processing, a markup language is a system for annotating a document in a way that is syntactically distinguishable from the text.

  The act of "annotating a document" is adding tags to your contents. There are many different tag systems, we call them different markup languages.

- What does "Hypertext" mean?

  Well, according to Wikipedia,

  > Hypertext is text displayed on a computer display or other electronic devices with references (hyperlinks) to other text that the reader can immediately access.
  
  In a word, when you see texts that lead you to other texts, consider them as hypertexts.

Here we are back to the topic "HTML". So, what does a HTML file look like? Let's take a look at this "hello, world" in HTML:

    <!DOCTYPE html>
    <html>

    <head>
    <meta charset="UTF-8">
    <title>Insert title here</title>
    </head>

    <body>
    </body>
    </html>

By the word "standard" you may see that most websites are written in HTML, or HTML takes a huge part in creating them. With HTML, you can add pictures, texts, etc in the way you want to a website or a document. HTML was first released in 1993, that's probably why it becomes so universal.

However, a "pure" HTML web page is usually static while most of the web pages that you see on the Internet seem to be dynamic. Well, that's because

> HTML can embed programs written in a scripting language such as JavaScript, which affects the behavior and content of web pages. Inclusion of CSS defines the look and layout of content. The World Wide Web Consortium (W3C), maintainer of both the HTML and the CSS standards, has encouraged the use of CSS over explicit presentational HTML since 1997.

### 2. Markdown

> Markdown is a lightweight markup language with plain text formatting syntax.

You can easily tell that Markdown is way much easier comparing to HTML while it can create a relevantly good document with basic layouts. I will not give any example here. It's usually used to write README files or taking notes, etc. It was first released in 2004.

However, one of the disadvantages of Markdown is that the language is so easy that it can't deal with complicated circumstances. If you want to insert a photo at a specific position or do any other "high-tech" stuff, you may be disappointed if you are trying to do that in **pure Markdown**.

Luckily, there is a solution to that. You can add HTML and CSS codes to a ".md" file.

### 3. CSS

----

## References

1. [HTML](https://en.wikipedia.org/wiki/HTML), from Wikipedia. Retrieved in January, 10, 2019.

2. [Markup language](https://en.wikipedia.org/wiki/Markup_language), from Wikipedia. Retrieved in January, 10, 2019.

3. "hello world" in HTML, from [【Html】第一个网页helloworld](https://www.cnblogs.com/carsonwuu/p/7470107.html). Retrieved in January, 11, 2019.

4. [Hypertext](https://en.wikipedia.org/wiki/Hypertext#cite_note-1), from Wikipedia. Retrieved in January, 11, 2019.

5. [Markdown](https://en.wikipedia.org/wiki/Markdown), from Wikipedia. Retrieved in January, 10, 2019.

----

## **[⇦ Previous: Adding Photos in Markdown](https://angelohyang.github.io/Blog/Jan.%202019/Adding%20Photos%20in%20Markdown)**

## **[🏡 Back To Home Page](https://angelohyang.github.io/Blog/)**