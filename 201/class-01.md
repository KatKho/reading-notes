# Read 01

Understanding these topics is essential in web development as they form the building blocks of creating functional and visually appealing websites. They provide insights into how data is transmitted between computers, how HTML, CSS, and JS files are processed by browsers, and how to create dynamic content using JavaScript. Additionally, knowledge of HTML attributes, element anatomy, and metadata allows for better organization, accessibility, and search engine optimization of web content. 

## Getting Started

1. Compose a short poem describing how HTTP sends data between computers.
   - ChatGPT helped me with this one:
    Through URLs, we find our desired place,
    HTTP requests to servers we embrace,
    With responses, data flows in our view,
    The web connects us, old and new.
   
2. Describe how HTML, CSS, and JS files are “parsed” in the browser.
   - The browser parses the HTML file first, and that leads to the browser recognizing any <link>-element references to external CSS stylesheets and any <script>-element references to scripts.
    As the browser parses the HTML, it sends requests back to the server for any CSS files it has found from <link> elements, and any JavaScript files it has found from <script> elements, and from those, then parses the CSS and JavaScript.
    The browser generates an in-memory DOM tree from the parsed HTML, generates an in-memory CSSOM structure from the parsed CSS, and compiles and executes the parsed JavaScript.
    As the browser builds the DOM tree and applies the styles from the CSSOM tree and executes the JavaScript, a visual representation of the page is painted 
    to the screen, and the user sees the page content and can begin to interact with it.
    
    Source: https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/How_the_Web_works

3. How can you find images to add to a Website?
   - To choose an image, go to Google Images and search for something suitable.
   
   Source: https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/What_will_your_website_look_like

4. How do you create a String vs a Number in JavaScript?
   - We use a similar structure to create both, but when we create a String we enclose the value in single or double quote marks. 
  
5. What is a Variable and why are they important in JavaScript?
   - Variable - is a name we give to a certain data type value to store it. 


## Introduction to HTML

1. What is an HTML attribute?
   - Additional information that goes inside an opening tag.
  
2. Describe the Anatomy of an HTMl element.
   - <Opening tag>content<closing tag>
3. What is the Difference between <article> and <section> element tags?
   - <article> encloses a block of related content that makes sense on its own without the rest of the page (e.g., a single blog post).
     <section> is similar to <article>, but it is more for grouping together a single part of the page that constitutes one single piece of functionality (e.g., a mini map, or a set of article headlines and summaries), or a theme. 

    Source: https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Document_and_website_structure

4. What Elements does a “typical” website include?
   - Header, navigation bar, content sections, images and media, footer, contact information.
  
5. How does metadata influence Search Engine Optimization?
   - Many <meta> elements include name and content attributes:
    name specifies the type of meta element it is; what type of information it contains. Specifying a description that includes keywords relating to the content of your page is useful as it has the potential to make your page appear higher in relevant searches performed in search engines (such activities are termed Search Engine Optimization, or SEO.)

    Source: https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/The_head_metadata_in_HTML

6. How is the <meta> HTML tag used when specifying metadata?
   - The <meta> HTML tag is used to specify metadata or additional information about an HTML document. Metadata provides information about the document itself, such as its title, character encoding, author, description, keywords, and more. 
  
    Source: ChatGPT

## Things I want to know more about
Coming soon...
