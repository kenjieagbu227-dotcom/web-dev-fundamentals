What is CSS?

CSS (Cascading Style Sheets) is used to style and design HTML elements — controlling layout, colors, fonts, and responsiveness.

🧩 3 Ways to Add CSS

1. Inline CSS

<p style="color: blue;">This is blue text</p>


2. Internal CSS

<style>
  p { color: red; }
</style>


3. External CSS

<link rel="stylesheet" href="style.css">



🖌️ Common CSS Properties

Property	Description	Example

color	Text color	color: red;
background-color	Background color	background-color: yellow;
font-size	Size of text	font-size: 20px;
margin	Outer spacing	margin: 10px;
padding	Inner spacing	padding: 15px;
border	Border style	border: 1px solid black;


🧠 Example: Simple Styled Page

<!DOCTYPE html>
<html>
<head>
  <title>My Styled Page</title>
  <style>
    body {
      background-color: #f0f0f0;
      font-family: Arial, sans-serif;
    }
    h1 {
      color: #2e86de;
      text-align: center;
    }
    p {
      color: #333;
      width: 80%;
      margin: auto;
    }
  </style>
</head>
<body>
  <h1>Welcome to CSS Basics</h1>
  <p>CSS makes your website look beautiful and organized!</p>
</body>
</html>

💬 

Practice by changing colors, font sizes, or margins — it’s the fastest way to learn visually.
