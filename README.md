> # README #

### Little note

I've read somewwhere that MARKDOWN is based of HTML and can be easelly converted to it. It also means that you can use all HTML commands in MD. 

For example, to make your text underlined use HTML command (< u > and < /u > without spaces) to get <u> underlined text </u>.

## QUOTES 

To mark something as qoute use (>) symbol in front of your text

> this is a quote

You can make qoutes with multiple rows, just use (>) symbol in your blank row

> this is 
>
> a quote
>
> with multiple
>
> rows

Also you can incapsulate your quotes in other quotes. Just use additional (>) symbol in your quote

> In fact 
>>you
>>>can
>>>>do
>>>>>it
>>>>>>as long
>>>>>>>as you
>>>>>>>>please

## HEADERS

There are 6 grades of titlles in markdown that you can use to format your titles. To do that frame your title with (#) symbol (In fact you can just put it only in front of you title). To differenciate between them use addicional (#) symbols

# title 1

## title 2

### title 3

#### title 4

##### title 5

###### title 6
<br></br>
Always divide your title with space otherwise it won't trigger or show exess (#) symbols

>#tiltle without space after (#)
>
>
> # title with incorrect spacing at the end#

## FORMATING

You can format your text in MARKDOWN, you can make it _italic_ or __bold__. To do that frame ypur text with (*) or (_) symbol without spaces for *italic* and double (*) or (_) symbols for **bold**. You cam also use HTML commands to do the same thing. 

> Use (*) or (_) or (< i > without spaces) for *italic*
>
> Use (**) or (__) or (< b > without spaces) for **bold**
>
> Use any combination of (*) or (_) or (< i > without spaces) AND (**) or (__) or (< b > without spaces) for __*italic bold*__

You can frame your text in ( ` ) symbol to mark your text as code.

`Hello world`

Some useful HTML commands
> < u > without spaces for <u>underlined</u>
>
> < s > without spaces for <s>crossed out</s>
>
> < mark > without spaces to <mark> highlight your text </mark>  
>
> < big > without spaces for <big> big text </big>
>
> < small > without spaces for <small> smaller text </small>
>
> < center > without spaces for alinging in 
> <center> center </center>
> To customize your text otherwise <b> use < font > command. </b> This command has 3 arguments: size, color and face.

> ### Syntax ###
> < font size="put a number here" color="put a color here" face="put a font name here (Arial, Calibri ect.)"> 
> 
>Let's try to use it with arguments size="4", color="cyan" and face="Comic sans ms"
>
> <font size="4" color="cyan" face="comic sans ms">Example of a custom font</font>

In future blocks we'll work with links, I'll leave a link to HTML commands guide. Try to experement yourself.

## LISTS

You can make lists in MARKDOWN. There 2 types of lists: numbered and unnumbered ones.

To create unnumbered list use (*) symbol in the begining of your row.

> Unnumbered list:
> * First item
> * Second item

You can also make **nested lists** by pressing (TAB) before  (*) symbol.
> Nested list example:
> * First item
>   * frist nested
>   * second nested
> * Second item   

To create numbered list use numbers with dot in the begining of your row.

> Numbered lis example
> 1. First item
> 2. Second item


## LINKS AND PICS

You can utilize links in MARKDOWN. 
To do that put your link in your file with https protocol
> https://www.youtube.com/watch?v=G1IbRujko-A&t=22s

You can also make hyper-refferences by using HTML command < a href >

> ### Syntax & Example
>
> Type without spaces:
>
> < a href = "put your URL here" > your text < /a >
>
> <a href="https://www.youtube.com/watch?v=SF-_47-oCtk"> Here, enjoy! :) </a>

You can also work with images in MARKDOWN. 

***To place an image in your document you must make some steps:***
1. Find and downlaod your image into your repository folder
2. Add your image via <code> git add </code> command in your terminal
3. Then use correct syntax in your file

> ### Syntax
> Write next command without spaces
>> ! [ unnecessary text can be used as title ] (filename with file format) 
>
> ### Example
>
> ![everybody loves a good Shrek meme](shrek.jpg)

<font size="4" color="pink" face="comic sans ms">So fancy....</font>