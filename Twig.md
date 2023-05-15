## Twig Cheat Sheet

# Basic Syntax

Twig templates are written in plain text with embedded Twig code. The Twig code can be used to access and manipulate the data that is passed to the template.

# Data Binding

Data is bound to Twig templates using the {{ }} syntax. For example, the following template will display the value of the name variable:


<h1>{{ name }}</h1>

# Expressions

Twig supports expressions in JavaScript. Expressions can be used to create dynamic content. For example, the following template will display the current date and time:


<h1>{{ new Date() }}</h1>

# Loops

Twig supports loops. Loops can be used to iterate over arrays and objects. For example, the following template will display a list of all the items in an array:


<ul>
  {% for item in items %}
    <li>{{ item }}</li>
  {% endfor %}
</ul>

# Conditionals

Twig supports conditionals. Conditionals can be used to control the flow of execution. For example, the following template will only display the message if the isLoggedIn variable is true:


{% if isLoggedIn %}
  <h1>You are logged in!</h1>
{% else %}
  <h1>You are not logged in!</h1>
{% endif %}

# Comments

Twig supports comments. Comments can be used to add notes to your templates. For example, the following template has a comment that explains what the {% for %} loop does:


<ul>
  {% for item in items %}
    <li>{{ item }}</li>
  {% endfor %}
  <!-- This loop iterates over the items array and displays each item -->
</ul>

# Importing Files

Twig allows you to import other files into your templates. This can be useful for importing CSS, JavaScript, or other files. For example, the following template imports a CSS file:


<!DOCTYPE html>
<html>
<head>
  <title>My Page</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <h1>My Page</h1>
</body>
</html>

# Custom Functions

Twig allows you to define custom functions that can be used in your templates. This can be useful for creating reusable functionality. For example, the following template defines a function that converts a number to a string:


<script>
  function toString(num) {
    return num.toString();
  }
</script>

<h1>{{ toString(123) }}</h1>

# Filters

Twig provides a number of filters that can be used to manipulate data. For example, the following template uses the upper filter to convert all the letters in the name variable to uppercase:


<h1>{{ name|upper }}</h1>

# Debugging

Twig templates can be debugged using the Twig debugger. To debug a template, start the Twig debugger and then open the template in a browser. The debugger will break at the first line of the template and you will be able to step through the code line by line.