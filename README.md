# Front-end Web: Class 1

Assess your current knowledge of HTML and CSS

## Class Competence

Students will: 

- Assess their current knowledge of HTML and CSS
- Identify: opening and closing tags and their attributes
- Use and memorize basic HTML syntax
- Envision the function of each HTML, CSS, and JS
- Investigate and identify HTML tags 



|    | Time   | Type  | Description |
| 1  | 5 min  |TT     | Intro, HTML, CSS, and JS |
| 2  | 10 min | Quiz  | Diagnostic Quiz |
| 3  | 10 min | Pair  | Pair up and research each question you missed |
| 4  | 5 min  | TT    | Quick intro to basic HTML syntax, tags, and boilerplate markup |
| 5  | 15 min | Pair  | With a partner research the tag list and markup the example |
| 6  | 10 min | Group | Discuss what tags you found that were applicable to the example |
| 7  | 10 min | break |  |
| 8  | 5 min  | TT    | Domains and Hosting |
| 9  | 20 min |I, Do, we Do | Semantic HTML the concept |
| 10 | 20 min | Solo  | Make a web page |


1 - Intro HTML, CSS, JS

2 - Quiz https://b.socrative.com/login/student/ room: 


3 - Pair lookup quiz questions you missed 

4 - HTML Syntax and boilerplate code. 
Case doesn’t matter, you should always use lowercase and - 
Tags 
Opening and closing
Some tags don’t close
No overlapping tags!
Attributes, values always quoted

5 - Pair up with a partner look at the tag list here: http://htmldog.com/references/html/tags/
Markup the example text using the tags that you think are most appropriate. 

6 - Discussion

7 - Break 

8 - Domains and hosting

9 - Semantic HTML concept. Tags add context and meaning to content on the page. The golden rule is always choose the tag that describes the element best, while understanding that sometimes there will be more than one, and often it will be a best judgement situation. 

What about tags like: <sarcasm>, <humor>. When we talk about CSS you will find that CSS provides aural styles. Imagine now that the computer can understand and express sarcasm. Whoa, that’s powerful.

Markup the example using boilerplate and sectional tags. Students follow up by directing the markup of the next document. 

10 - Make a web page. We will continue to work on and add features to the pages you create. As of today the page will provide little design, you will be adding more as class progresses.  Choose one of the following:

Make a web page for the app you created at Summer Academy
Make a web page for yourself. 
Markup Sample document 
































# Front-end-Web-Class-1

## What is HTML?

HTML is Hyper Text Markup language. Markup languages are used to describe, or markup, information. Imagine this: 

> Makeschool 
>
> Email
>
> hello@makeschool.com
>
> Address
>
> 1547 Mission Street 
>
> San Francisco, CA 94103

Looks good, and you understand this but, how about this:

```
<header>
  <h1>Makeschool</h1>
  <address>
    Email hello@makeschool.com
    Address 1547 Mission Street
    San Francisco, CA 94103
  </address>
</header>
```

Actually it might look more like this: 

```
<header>
  <h1>Makeschool</h1>
  <img src="logo.gif">
  <address>
    <ul>
      <li><strong>Email</strong><em>hello@makeschool.com</em></li>
      <li><strong>Address</strong><em>1547 Mission Street</em></li>
      <li>San Francisco, CA 94103<br></li>
  </address>
</header>
```

### Tags and syntax

Are the basic syntax of HTML. Tags begin with an opening tag: <tag> and end with a closing tag: </tag>. Notice the /.

If a tag surrounds content there muts be a closing tag. A few tags do not surround content and are written as a single tag
without a closing tag. See the <br> and <img> tags above. 

Tags can be nested but can not overlap! For example: 

Good!

```
<header>
  <h1>Title</h1>
</header>
```

Bad!

```
<header>
  <h1>Title
</header> <-- Closes before h1!
</h1> 
```

Exercise: Mark up the content provided. Use the list of tags here. Find the most appropriate tag for each content element. 




