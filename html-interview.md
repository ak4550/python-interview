## HTML Interview Questions:
#### 1. What is HTML?
Answer: HTML stands for HyperText Markup Language. It is the standard markup language used to create the structure of web pages. HTML consists of a series of elements, each represented by tags, which define the content and layout of a webpage.

#### 2. What is the difference between HTML and XHTML?
Answer: HTML (HyperText Markup Language) and XHTML (eXtensible HyperText Markup Language) are both markup languages used to create web pages. The main difference is in the syntax and rules. XHTML is more strict and follows XML rules, requiring well-formed documents. HTML is more forgiving and allows for more flexibility in terms of syntax.

#### 3. Explain the purpose of the DOCTYPE declaration in HTML.
Answer: The DOCTYPE declaration is used to specify the version of HTML or XHTML that a web page is using. It helps the browser to render the page correctly by providing information about the document type and version. For example:
```
<!DOCTYPE html>
```
This declaration is for HTML5, the latest version of HTML.

#### 4. What is the difference between \<div\> and \<span\> in HTML?
Answer: Both \<div\> and \<span\> are container elements, but they are used in different contexts. \<div\> is a block-level element and is used to group and structure content, often for layout purposes. \<span\> is an inline element and is used to apply styles or scripting to a specific part of the text within a block-level element.

#### 5. Explain the difference between the \<script\> tag placement - in the \<head\> vs. at the end of the \<body\> in HTML.
Answer: Placing the \<script\> tag in the \<head\> section means that the script will be loaded and executed before the HTML content is rendered. This is beneficial for scripts that need to run early in the page load process.

On the other hand, placing the \<script\> tag at the end of the \<body\> allows the HTML content to load first, and then the script is loaded and executed. This is useful for scripts that don\'t need to interfere with the initial page rendering and can run after the main content has loaded\.