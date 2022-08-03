# HTML_Interview_Questions
HTML questions asked in Interviews.

Introduction

Before starting with the interview questions on HTML Language, let’s first go through HTML, what is HTML, the career opportunities it provides, etc.

HTML stands for HyperText Markup language. It is a standard text formatting language used for developing web pages released in 1993. HTML is a language that is interpreted by the browser and it tells the browser what to display and how to display.

HTML is an important language to learn if anyone wants to work in the web development domain [Web designers, Web Developers]. HTML alone is not sufficient for a web developer because HTML only defines the structure of the data that will be rendered on the browser in a webpage, to make it visually appealing and to make it functional, we will need to use CSS and Javascript respectively. 

The latest version of HTML is HTML5. There are two main components in HTML language, Tags and Attributes. The below image shows some basic HTML tags and attributes.

![image](https://user-images.githubusercontent.com/81725794/182292498-dae2eefa-36db-40f3-90c7-bef77739014b.png)

1. Are the HTML tags and elements the same thing?

No. HTML elements are defined by a starting tag, may contain some content and a closing tag.For example, <h1>Heading 1</h1> is a HTML element but just <h1> is a starting tag and </h1> is a closing tag.

2. What are tags and attributes in HTML?

Tags are the primary component of the HTML that defines how the content will be structured/ formatted, whereas Attributes are used along with the HTML tags to define the characteristics of the element. For example, <p align=” center”>Interview questions</p>, in this the ‘align’ is the attribute using which we will align the paragraph to show in the center of the view.

3. What are void elements in HTML?

HTML elements which do not have closing tags or do not need to be closed are Void elements. For Example <br />, <img />, <hr />, etc.

4. What is the advantage of collapsing white space?

In HTML, a blank sequence of whitespace characters is treated as a single space character, Because the browser collapses multiple spaces into a single space character and this helps a developer to indent lines of text without worrying about multiple spaces and maintain readability and understandability of HTML codes.

5. What are HTML Entities?

In HTML some characters are reserved like ‘<’, ‘>’, ‘/’, etc. To use these characters in our webpage we need to use the character entities called HTML Entities. Below are a few mapping between the reserved character and its respective entity character to be used.

![Screenshot (981)](https://user-images.githubusercontent.com/81725794/182524905-07cc67c8-3791-4b49-83b3-5c1b3ee7fd0b.png)

6. What are different types of lists in HTML?

![image](https://user-images.githubusercontent.com/81725794/182524968-d136cd7c-1f0a-4133-afe9-aff8af509288.png)

7. What is the ‘class’ attribute in HTML?

The class attribute is used to specify the class name for an HTML element. Multiple elements in HTML can have the same class value. Also, it is mainly used to associate the styles written in the stylesheet with the HTML elements.

8. What is the difference between the ‘id’ attribute and the ‘class’ attribute of HTML elements?

Multiple elements in HTML can have the same class value, whereas a value of id attribute of one element cannot be associated with another HTML element.

9. Define multipart form data?

Multipart form data is one of the values of the enctype attribute. It is used to send the file data to the server-side for processing. The other valid values of the enctype attribute are text/plain and application/x-www-form-urlencoded.

10. Describe HTML layout structure.

Every web page has different components to display the intended content and a specific UI. But still, there are few things which are templated and are globally accepted way to structure the web page, such as:

<header>: Stores the starting information about the web page.
<footer>: Represents the last section of the page.
<nav>: The navigation menu of the HTML page.
<article>: It is a set of information.
<section>: It is used inside the article block to define the basic structure of a page.
<aside>: Sidebar content of the page.
  
11. How to optimize website assets loading?
  
To optimize website load time we need to optimize its asset loading and for that:

CDN hosting - A CDN or content delivery network is geographically distributed servers to help reduce latency.
File compression - This is a method that helps to reduce the size of an asset to reduce the data transfer
File concatenation - This reduces the number of HTTP calls
Minify scripts - This reduces the overall file size of js and CSS files
Parallel downloads - Hosting assets in multiple subdomains can help to bypass the download limit of 6 assets per domain of all modern browsers. This can be configured but most general users never modify these settings.
Lazy Loading - Instead of loading all the assets at once, the non-critical assets can be loaded on a need basis.
  
12. What are the various formatting tags in HTML?
  
 HTML has various formatting tags:

<b> - makes text bold
<i> - makes text italic
<em> - makes text italic but with added semantics importance
<big> - increases the font size of the text by one unit
<small> - decreases the font size of the text by one unit
<sub> - makes the text a subscript
<sup> - makes the text a superscript
<del> - displays as strike out text
<strong> - marks the text as important
<mark> - highlights the text
<ins> - displays as added text
  
13. What are the different kinds of Doctypes available?
