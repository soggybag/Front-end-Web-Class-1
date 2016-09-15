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




