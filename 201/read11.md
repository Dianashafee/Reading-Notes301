# WHAT IS EJS?

- E in EJS is for Embedded, Ejs is simple and effective template engine for JavaScript. EJS is the simple template which allows developers to create the HTML page with plain JavaScript. Ejs provide fast compilation and rendering and include both server and browser support.

![](https://cdn3.f-cdn.com/contestentries/218364/11014203/55572126eae23_thumb900.jpg)


### EJS is a template system. You define HTML pages in the EJS syntax and you specify where various data will go in the page. Then, your app combines data with the template and "renders" a complete HTML page where EJS takes your data and inserts it into the web page according to how you've defined the template. For example, you could have a table of dynamic data from a database and you want EJS to generate the table of data according to your display rules. It saves you from the drudgery of writing code to dynamically generate HTML based on data. 

### EJS is compatible with Express for back-end use as it hooks into the View engine architecture that Express provides and lets you render web pages to the client with res.render() in Express.

# Why do we need to use EJS ?
-  It allows you to do things like conditional statements and loops, and give you the ability to break the pages into more modular components (for example, you can have one template with the header in it, and then include that in every other page without having to copy and paste the code). That said, there's nothing stopping you using pure HTML - you just won't get any of those features.

# EJS tags :
* <% 'Scriptlet' tag, for control-flow, no output
* <%_ ‘Whitespace Slurping’ Scriptlet tag, strips all whitespace before it
* <%= Outputs the value into the template (HTML escaped)
* <%- Outputs the unescaped value into the template
* <%# Comment tag, no execution, no output
* <%% Outputs a literal '<%'
* %> Plain ending tag
* -%> Trim-mode ('newline slurp') tag, trims following newline
* _%> ‘Whitespace Slurping’ ending tag, removes all whitespace after it
