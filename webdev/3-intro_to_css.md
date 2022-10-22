# What is CSS?
CSS stands for Cascading Style Sheets, and it is used to style and layout your website.

## How to use CSS
Create a new file then end the file name with `.css`

To connect the css to the html document, add a link in the `<head>` tag your html document.
```html
<!DOCTYPE html>
<html>
<head>
  <link rel="stylesheet" href="css_file_name.css">
</head>
</html>
```

## Components of a css element

```css
selector {
  property: value;
  property: value;
}
```

---
## Sample:

Code:

HTML document: (index.html)
```html
<!DOCTYPE html>
<html>
<head>
  <title>Introduction to CSS</title>
  <link rel="stylesheet" href="styles.css">
</head> 
<body>

<h1>This is the first heading</h1>
<h2>This is the second heading</h2>

</body>
</html>
```

CSS document: (styles.css)
```css
h1{
  color:blue;
  font-size: 40px;
}

h2{
  background-color: red;
  font-size: 10px
}
```

Output:

![](media/intro_to_css.png)

~Nolawi