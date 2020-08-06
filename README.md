# What I learned Week-12.

**DOM** - Stands for Document Object Model.

- This is a programming interface for HTML documents that represents the page so that programs like JS can change the structure, content and style. It represents the documents as nodes and objects so that programming languages can connect.
- DOM is not a programming language but without it JS would not have any model or notion of the web pages.

**How to access DOM**
- Simply by placing *<script>* tag in HTML.

**Methods**

- **document.querySelector()** - This method will return first element in a document that matches a specified selector. Will return Null if no matches are found.
    *ex.* document.querySelector('#name') <= Returns Id "name".

- **document.querySelectorAll()** - This will return a static NodeList representing a list of document elements. 
    *ex.* document.querySelectorAll('p') <= Obtains NodeList of all <p> tag elements.

- **addEventListener()** - This method works by adding a function that will implement to the event listener for the specified event on the event target on which it is called.
    *ex.* target.addEventListener('click', function);

    
