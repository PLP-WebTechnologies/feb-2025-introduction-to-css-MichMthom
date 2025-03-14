
/* Global Styles */

* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

body {
  font-family: Arial, sans-serif;
  line-height: 1.6;
  color: #333;
  background-color: #f9f9f9;
}

/* Class Selectors */
.container {
  max-width: 800px;
  margin: 40px auto;
  padding: 20px;
  background-color: #fff;
  border: 1px solid #ddd;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

.header {
  background-color: #333;
  color: #fff;
  padding: 10px;
  text-align: center;
}

/* ID Selectors */

#logo {
  width: 100px;
  height: 100px;
  margin: 20px auto;
  border-radius: 50%;
}
#hero-image {
  width: 100%;
  height: 300px;
  object-fit: cover;
  margin-bottom: 20px;
}

/* Typography */

h1 {
  font-size: 36px;
  font-weight: bold;
  margin-bottom: 10px;
}

p {
  font-size: 18px;
  margin-bottom: 20px;
}

/* Links */

a {
  text-decoration: none;
  color: #337ab7;
}

a:hover {
  color: #23527c;
}

/* Tasks */

.task {
  background-color: #f0f0f0;
  padding: 10px;
  border-bottom: 1px solid #ccc;
}

.task:hover {
  background-color: #e0e0e0;
}


To link this external CSS file to an HTML page, add the following line of code in the <head> section of the HTML file:


<link rel="stylesheet" type="text/css" href="style.css">


Here's an example HTML file that uses the styles defined in the style.css file:


<!DOCTYPE html>
<html>
<head>
  <title>Styled HTML Page</title>
  <link rel="stylesheet" type="text/css" href="style.css">
</head>
<body>
  <div class="container">
    <div class="header">
      <h1>Welcome to our website!</h1>
    </div>
    <img id="hero-image" src="hero-image.jpg" alt="Hero Image">
    <div class="task">
      <p>This is a task item.</p>
    </div>
    <div class="task">
      <p>This is another task item.</p>
    </div>
    <p><a href="#">Learn more about our services.</a></p>
  </div>
</body>
</html>
