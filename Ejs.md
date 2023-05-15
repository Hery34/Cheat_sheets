# EJS Cheat Sheet

## Introduction

EJS (Embedded JavaScript) is a templating engine that allows you to generate HTML markup with plain JavaScript. It is easy to learn and use, and is widely used in Node.js web applications.

## Installation

To use EJS in your Node.js project, you need to install it first. You can install EJS using npm, the Node.js package manager:

`npm install ejs`

## Basic Syntax

EJS uses special tags to embed JavaScript code in HTML markup. The most commonly used tags are:

- <% %>: Executes the JavaScript code inside the tags.
- <%= %>: Prints the value of the JavaScript expression inside the tags.
- <%- %>: Prints the value of the JavaScript expression inside the tags, but HTML-escapes the output.

Here's an example of how to use EJS tags in HTML markup:

<ul>
  <% for (var i = 0; i < fruits.length; i++) { %>
    <li><%= fruits[i] %></li>
  <% } %>
</ul>

In this example, the <% %> tags are used to execute a for loop that iterates over an array of fruits, and the <%= %> tag is used to print the value of each fruit in an HTML list item.

## Passing Data to Templates

To pass data to an EJS template, you can use the render method of the EJS module. The render method takes two arguments: the path to the EJS template file, and an object that contains the data to be passed to the template.

Here's an example of how to pass data to an EJS template:

const ejs = require('ejs');
const data = { name: 'John', age: 30 };
const template = 'Hello <%= name %>, you are <%= age %> years old.';
const html = ejs.render(template, data);
console.log(html);

In this example, the render method is used to render an EJS template that contains two variables: name and age. The data object is passed to the render method as the second argument, and the resulting HTML is printed to the console.

## Including Partials

EJS allows you to include partial templates in your main template using the <%- include %> tag. The include tag takes the path to the partial template as its argument.

Here's an example of how to include a partial template in an EJS template:

<!DOCTYPE html>
<html>
  <head>
    <title><%= title %></title>
  </head>
  <body>
    <%- include('header') %>
    <h1><%= title %></h1>
    <p><%= content %></p>
    <%- include('footer') %>
  </body>
</html>

In this example, the header and footer partial templates are included in the main template using the include tag.