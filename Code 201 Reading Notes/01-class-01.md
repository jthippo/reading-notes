# class-01 (102 recap)

### Getting started

#### Compose a short poem describing how HTTP sends data between computers.

There once was a browser who requested copy of HTTP from server
The server approved the request and sent client an OK message
HTTP is sent in packets
The browser pieces them together
And then the client can access the webpage

#### Describe how HTML, CSS, and JS files are “parsed” in the browser.

HTML parsed first, with requests sent to server for CSS and JS links found within the HTML.

#### How do you create a String vs a Number in JavaScript?

A string is always in inverted commas; a number is not.

#### What is a Variable and why are they important in JavaScript?

A variable is named storage (defined by "let"). Variables can then be manipulated and used in any number of ways.

### Intro to HTML

#### What is an HTML attribute?

An attribute provides additional information about HTML elements, e.g. src, style, href.

#### Describe the Anatomy of an HTMl element.

< opening tag > content </ closing tag >

#### What is the Difference between <article> and <section> element tags?

An article should make sense by itself, independent from the HTML (e.g. blog post, news story). Section is used to define sections of a webpage.

#### What Elements does a “typical” website include?

- Header
- Navigation bar
- Main content
- Sidebar
- Footer

#### How does metadata influence Search Engine Optimization?

Search engines crawl web pages for keywords and other information, then compare that with the metadata to organise the page in search engine results pages. Metadata is a part of the search engine's language and helps them better understand the topic of web pages and content, and helps them display more relevant results.

#### How is the <meta> HTML tag used when specifying metadata?

Metadata is information about data. <meta> tags always go inside the <head> element, and are typically used to specify character set, page description, keywords, author of the document, and viewport settings.

### Miscellaneous

#### What is the first step to designing a Website?

Define what you want to accomplish with it.

#### Why should you use an <h1> element over a <span> element to display a top level heading?

Search engines do not use <span>, they look specifically for <h1>.

#### What are the benefits of using semantic tags in our HTML?

- Search engines will consider its contents as important keywords
- Screen readers can use it help users navigate a page
- Finding blocks of meaningful code is significantly easier
- Suggests to the developer the type of data that will be populated

#### Describe 2 things that require JavaScript in the Browser?

- Dynamic behaviour
- Operations on strings

#### How can you add JavaScript to an HTML document?

By using the <script> element.
