# Things About HTML, Markdown, CSS, LaTeX, and JavaScript

***Last edit: 00:08:42 1/16/2019***

When it comes to creating a web page, the word HTML occurs constantly. As I study further and further, words like Markdown and CSS become familiar to me. Although I have never written anything in HTML, JavaScript, or CSS directly before, I believe it is of great use to **gather some information** about them.

----

## Summary

### Markup Languages

Before we go and learn some famous markup languages, here are some questions we should focus on first:

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

Here are some popular markup languages:

#### 1. HTML

HTML stands for "Hypertext Markup Language".

> ![how-to-meet-ladies](https://raw.githubusercontent.com/AngeloHYang/Blog/master/Jan.%202019/html.jpg)\
> No, not "How to Meet Ladies"! 😂

According to Wikipedia,

> HTML is the standard markup language for creating web pages and web applications.

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

By the word "standard" you may see that most websites are written in HTML, or HTML takes a huge part in creating them. With HTML, you can add pictures, texts, and other things in the way you want to a website or a document. HTML was **first released in 1993**, that's probably why it becomes so universal.

However, a "pure" HTML web page is usually static while most of the web pages that you see on the Internet seem to be dynamic. Well, that's because

> HTML can embed programs written in a scripting language such as JavaScript, which affects the behavior and content of web pages. Inclusion of CSS defines the look and layout of content. The World Wide Web Consortium (W3C), maintainer of both the HTML and the CSS standards, has encouraged the use of CSS over explicit presentational HTML since 1997.

#### 2. Markdown

> Markdown is a lightweight markup language with plain text formatting syntax.

You can easily tell that Markdown is way much easier comparing to HTML while it can create a relevantly good document with basic layouts. I will not give any example here. It's usually used to write README files or taking notes, etc. It was **first released in 2004**.

However, one of the disadvantages of Markdown is that the language is so easy that it can't deal with complicated circumstances. If you want to insert a photo at a specific position or do any other "high-tech" stuff, you may be disappointed if you are trying to do that in **pure Markdown**.

Luckily, there is a solution to that. You can add HTML and CSS codes to a ".md" file.

#### 3. LaTeX

> LaTeX (/ˈlɑːtɛx/ LAH-tekh or /ˈleɪtɛx/ LAY-tekh; a shortening of Lamport TeX) is a document preparation system. When writing, the writer uses plain text as opposed to the formatted text found in WYSIWYG ("what you see is what you get") word processors like Microsoft Word, LibreOffice Writer and Apple Pages. The writer uses markup tagging conventions to define the general structure of a document (such as article, book, and letter), to stylise text throughout a document (such as bold and italics), and to add citations and cross-references. A TeX distribution such as TeX Live or MikTeX is used to produce an output file (such as PDF or DVI) suitable for printing or digital distribution.

Funny thing about its name is that:

> Within the typesetting system, its name is stylised as ![LaTeX](https://upload.wikimedia.org/wikipedia/commons/thumb/9/92/LaTeX_logo.svg/1920px-LaTeX_logo.svg.png)

But you may also go with LaTeX.

It was **initially released in 1983**.

#### 4. Scribe, GML, SGML, XML, etc

### Style Sheet Language

- What does "Style Sheet Language" mean?
  
  > A style sheet language, or style language, is a computer language that expresses the presentation of structured documents.

  In short, a style sheet language tells your contents in a document how to display.

#### 1. CSS

> Cascading Style Sheets (CSS) is a style sheet language used for describing the presentation of a document written in a markup language like HTML.

It isn't hard to tell from "cascading" that CSS is used to deal with complicated issues with layouts, fonts, colors, etc.

It looks like this:

    h1 { color: white;
    background: orange;
    border: 1px solid black;
    padding: 0 0 0 0;
    font-weight: bold;
    }
    /* begin: seaside-theme */
    body {
    background-color:white;
    color:black;
    font-family:Arial,sans-serif;
    margin: 0 4px 0 0;
    border: 12px solid;
    }

The language was **first released in 1996**.

> CSS is a cornerstone technology of the World Wide Web, alongside HTML and JavaScript.\
> In addition to HTML, other markup languages support the use of CSS including XHTML, plain XML, SVG, and XUL.

### Programming Languages

#### 1. JavaScript

> JavaScript often abbreviated as JS, is a high-level, interpreted programming language that conforms to the ECMAScript specification. It is a language that is also characterized as dynamic, weakly typed, prototype-based and multi-paradigm.

NO! JavaScript ≠ Java.

![Java 和 Javascript的关系，就和雷锋和雷峰塔一样](http://www.runoob.com/wp-content/uploads/2014/06/9c32a3e498cb5822f8fb3cd0d07b4a78_m.jpg)

Rumors has it that the reason why it is called JavaScript, with the word "Java" inside, is that Java was popular then and naming it as "**Java**Script" also made this language popular.

This language is used in webs very often. It was **initially released in 1995**.

----

## Table of Languages

| Language | Type | Release Year |
| ---- | ---- | ----: |
| HTML | Markup Language | 1993 |
| Markdown | Markup Language | 2004 |
| LaTeX | Markup Language | 1983 |
| CSS | Style Sheet Language | 1996 |
| JavaScript | Programming Languages | 1995 |

----

## References

1. [HTML](https://en.wikipedia.org/wiki/HTML), from Wikipedia. Retrieved in January, 10, 2019.

2. [How to Meet Ladies](http://devhumor.com/media/html-how-to-meet-ladieshttp://devhumor.com/media/html-how-to-meet-ladies), from <http://devhumor.com/media/html-how-to-meet-ladies>, submitted by: admin. Retrieved in January, 14, 2019.

3. [Markup language](https://en.wikipedia.org/wiki/Markup_language), from Wikipedia. Retrieved in January, 10, 2019.

4. "hello world" in HTML, from [【Html】第一个网页helloworld](https://www.cnblogs.com/carsonwuu/p/7470107.html). Retrieved in January, 11, 2019.

5. [Hypertext](https://en.wikipedia.org/wiki/Hypertext#cite_note-1), from Wikipedia. Retrieved in January, 11, 2019.

6. [Markdown](https://en.wikipedia.org/wiki/Markdown), from Wikipedia. Retrieved in January, 10, 2019.

7. [LaTex](https://en.wikipedia.org/wiki/LaTeX), from Wikipedia. Retrieved in January, 15, 2019.

8. [Style sheet language](https://en.wikipedia.org/wiki/Style_sheet_language), from Wikipedia. Retrieved in January, 15, 2019.

9. [CSS](https://en.wikipedia.org/wiki/Cascading_Style_Sheets), from Wikipedia. Retrieved in January, 15, 2019.

10. [JavaScript](https://en.wikipedia.org/wiki/JavaScript), from Wikipedia. Retrieved in January, 15, 2019.

11. Photo [Java 和 Javascript的关系，就和雷锋和雷峰塔一样](http://www.runoob.com/wp-content/uploads/2014/06/9c32a3e498cb5822f8fb3cd0d07b4a78_m.jpg),  from 菜鸟教程. Retrieved in 1/15/2019.

12. [Java 和 Javascript的关系](http://www.runoob.com/w3cnote/java-and-javascript-relationship.html), from 菜鸟教程. Retrieved in 1/15/2019.

----

## **[⇦ Previous: Adding Photos in Markdown](https://angelohyang.github.io/Blog/Jan.%202019/Adding%20Photos%20in%20Markdown)**

## **[🏡 Back To Home Page](https://angelohyang.github.io/Blog/)**