## A Short Bootstrap Tutorial on the What, Why, and How
URL: https://www.toptal.com/front-end/what-is-bootstrap-a-short-tutorial-on-the-what-why-and-how

### What is Bootstrap?
- Bootstrap is a powerful toolkit - a collection of HTML, CSS, and JavaScript tools for creating and building web pages and web applications
- Originally created by Twitter

### Benefits
- Responsive by design
- Re-usable components
- Rich extensibility using JavaScript

### Download
- Bootstrap is available in two forms:
  1. Precompiled Version:
    - Vanilla CSS
    - Note: All styles can be overridden later
  2. Source Code Version:
    - Can choose between `Less` and `Sass` preprocessor version
    - Provides flexibility to ambitious developers to customize and build their own version of Bootstrap
- URL: http://getbootstrap.com/getting-started/#download

### File Structure
- Precompiled Version comes with
  1. CSS files
  2. JavaScript files
  3. Font files: Glyphicons fonts folder should be on the same level as the CSS folder
- HTML: HTML templates can be copied and modified from Bootstrap tutorial page
```
bootstrap/
├── css/
│   ├── bootstrap.css
│   ├── bootstrap.css.map
│   ├── bootstrap.min.css
│   ├── bootstrap.min.css.map
│   ├── bootstrap-theme.css
│   ├── bootstrap-theme.css.map
│   ├── bootstrap-theme.min.css
│   └── bootstrap-theme.min.css.map
├── js/
│   ├── bootstrap.js
│   └── bootstrap.min.js
└── fonts/
    ├── glyphicons-halflings-regular.eot
    ├── glyphicons-halflings-regular.svg
    ├── glyphicons-halflings-regular.ttf
    ├── glyphicons-halflings-regular.woff
    └── glyphicons-halflings-regular.woff2
```

### Getting started
Copy the HTML below to begin working with a minimal Bootstrap document
```HTML
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <!-- The above 3 meta tags *must* come first in the head; any other head content must come *after* these tags -->
    <title>Bootstrap Template</title>

    <!-- Bootstrap CSS-->
    <link href="css/bootstrap.min.css" rel="stylesheet">
  </head>
  <body>
    <h1>Hello, world!</h1>
    <!-- jQuery (necessary for Bootstrap's JavaScript plugins) -->
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.2/jquery.min.js"></script>

    <!-- Include all compiled plugins (below), or include individual files as needed -->
    <!-- Bootstrap JS-->
    <script src="js/bootstrap.min.js"></script>
  </body>
</html>
```
