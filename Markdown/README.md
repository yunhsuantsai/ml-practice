# Markdown Tutorial

### Why do we need it?

* It is a simple way to write formatted elements for the web
* It becomes the writing standard for academics, scientists, writers, and many more
* Websites like [GitHub](https://github.com) and [Bitbucket](https://bitbucket.org/) use Markdown to style their comments. It takes `README.md` in the repository as documentation and display it on the web.

### How does it works

**Markdown app** help to translate plaintext into html document 

![Generate a html document by markdwon app](https://d33wubrfki0l68.cloudfront.net/75cdd78aba218a9abbfe91d2ba2cf540a7502d8c/553fa/assets/images/process.png)

### Practice

We use [Dillinger](https://dillinger.io/), an online markdown editor to write markdown. You can choose other preference one markdown app.

##### Italics and Bold

Surround words with an underscore `_` to make it _italics_.
Surround words with double asterisk `**` to make it **bold**.

```
_I am italic style_
**I am bold style**
```
_I am italic style_

**I am bold style**

##### Headers

To make headers in Markdown, you preface the phrase with a hash mark `#`

There are six types of headers, in decreasing sizes:

```
# This is header one
## This is header two
### This is header three
#### This is header four
##### This is header five
###### This is header six
```

# This is header one
## This is header two
### This is header three
#### This is header four
##### This is header five
###### This is header six

##### Links

Links could be either URL path or relative path.

###### Inline link

To create an inline link, you wrap the link text in brackets `[ ]`, and then you wrap the link in parenthesis `( )`

```
[Visit Data Team Shared Resources!](https://bitbucket.mfortune.co.uk/projects/DT/repos/data-team-shared-resources/browse?at=refs/heads/pre-release)
```

[Visit Data Team Shared Resources!](https://bitbucket.mfortune.co.uk/projects/DT/repos/data-team-shared-resources/browse?at=refs/heads/pre-release)

```
[README.md of this repository](../README.md)
```

[README.md of this repository](../README.md)

###### Reference link

The link is actually a reference to another place in the document. You put reference in the second set of parenthesis `[ ]`, and define link in other line.

```
[Visit Data Team Shared Resources!][data team shared folder repository]

[data team shared folder repository]: https://bitbucket.mfortune.co.uk/projects/DT/repos/data-team-shared-resources/browse?at=refs/heads/pre-release
```

[Visit Data Team Shared Resources!][data team shared folder repository]

[data team shared folder repository]: https://bitbucket.mfortune.co.uk/projects/DT/repos/data-team-shared-resources/browse?at=refs/heads/pre-release

##### Images

Images also have two styles, just like links, and both of them render the exact same way. The difference between links and images is that images are prefaced with an exclamation point `!`.

```
![Intouch Reports LOGO](https://backoffice.mfortune.co.uk/repmanagement/pages/img/logo2.png)
![Intouch Reports LOGO][IRL]

[IRL]: https://backoffice.mfortune.co.uk/repmanagement/pages/img/logo2.png
```

![Intouch Reports LOGO](https://backoffice.mfortune.co.uk/repmanagement/pages/img/logo2.png)
![Intouch Reports LOGO][IRL]

[IRL]: https://backoffice.mfortune.co.uk/repmanagement/pages/img/logo2.png

##### Blockquotes

A blockquote is a sentence or paragraph that's been specially formatted to draw attention to the reader. You can use it on a quote from other source, for example:

> "Information is the oil of the 21st century, and analytics is the combustion engine." ~ Peter Sondergaard, SVP, Gartner Research

To create a block quote, all you have to do is preface a line with the "greater than" caret `>`.

```
> "I am just a child who has never grown up. I still keep asking these 'how' and 'why' questions. Occasionally, I find an answer." ~ Stephen Hawking
```

> "I am just a child who has never grown up. I still keep asking these 'how' and 'why' questions. Occasionally, I find an answer." ~ Stephen Hawking


##### Lists

There are two types of lists: unordered and ordered, which is distinguished by with number index or not.

```
* Unordered Item 1
* Unordered Item 2
* Unordered Item 3
```

* Unordered Item 1
* Unordered Item 2
* Unordered Item 3

```
1. Ordered Item 1
2. Ordered Item 2
3. Ordered Item 3
```

1. Ordered Item 1
2. Ordered Item 2
3. Ordered Item 3

Occasionally, you might find the need to make a list with more depth, or, to nest one list within another. All you have to do is to remember to indent each asterisk one space more than the preceding item

```
* Item 1
    1. Sub item 1-1
    2. Sub item 1-2
* Item 2
    * Sub item 2-1
    * Sub item 2-2
```

* Item 1
    1. Sub item 1-1
    2. Sub item 1-2
* Item 2
    * Sub item 2-1
    * Sub item 2-2

##### Paragraphs

You can put an empty line between sentences to separate them into different sections. It is called **hard break**

```
To see a World in a Grain of Sand

And a Heaven in a Wild Flower,

Hold Infinity in the palm of your hand 

And Eternity in an hour.
```

To see a World in a Grain of Sand

And a Heaven in a Wild Flower,

Hold Infinity in the palm of your hand 

And Eternity in an hour.

However, sometimes you don't want to separated them to this large gap. You can put two space between sentences in order to separate them to different lines. It is called **soft break**.

```
To see a World in a Grain of Sand  
And a Heaven in a Wild Flower,  
Hold Infinity in the palm of your hand  
And Eternity in an hour.
```

To see a World in a Grain of Sand  
And a Heaven in a Wild Flower,  
Hold Infinity in the palm of your hand  
And Eternity in an hour.

##### Highlights

To emphasize some section of content, you can wrap content with `` ` `` for one line or three `` ` `` for multiple lines. 

One line example:  
Please replace `${package.json.version}` into real version number.

Multiple lines example:  
Please take a look at following codes:
```
# Following code will list all direcotries and files, including hidden file in your current directory
$ ls -al
```

##### Tables

When you need a table to have better alignment, you need at least three lines to create a table.  
First line, You use `|` to separate column names.  
Second line, you use `| ------ | ------ |`, same column number as first line but only `-` as content.
Third line, you use `|` to separate row values.

You can decide your column and row number based on your need. For example:


```
| Column1 | Column2 |
| ------ | ------ |
| field 0-0 | field 0-1 |
| field 1-0 | field 1-1 |
```

| Column1 | Column2 |
| ------ | ------ |
| field 0-0 | field 0-1 |
| field 1-0 | field 1-1 |

Now, you can start to write a markdown document. Enjoy it!
