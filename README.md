# w3.css-without-w3-tag

Hi everybody !
For some time now I have been using the ex-framework of w3schools.com - W3.css which provides a lot of CSS classes to facilitate web development. 
However, after using it a lot, I was thrown by the "w3-" prefix preceding the class name. If it's a good thing not to be confused with the name of your own classes, to write hundreds of times, it can become a tedious task. I then had the idea to remove the prefix "w3-" classes of this great tool designed by Jan Egil and Borge Refsnes ... Many thanks to them for this contribution. To use this CSS framework, simply refer to the w3.css documentation at this url: https://www.w3schools.com/w3css/
and use the same class names without putting "w3-" in front. That's it, it's simple, it accelerates even more the development css. Sincerely, Raf for www.sns.pm

How to use :
(inspired from https://www.w3schools.com/w3css/default.asp)

<!DOCTYPE html>
<html lang="en">
<head>
  
	<title>w3.css-without-w3-tag</title>
  
  <link rel="stylesheet" href="w3css-Customized.css">
	<link rel="stylesheet" href="your_style_here.css">
  
</head>
<body>
  
  <header class="container teal">
    <h1>This is a title</h1>
  </header>

  <article class="container">
    <p>Hello World !</p>
  </article>

  <footer class="container teal">
    <h5>Footer</h5>
  </footer>

</body>
</html>
