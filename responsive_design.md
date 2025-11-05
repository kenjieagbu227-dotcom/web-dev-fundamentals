What is Responsive Design?

Responsive Design means creating websites that automatically adjust their layout and size depending on the device (desktop, tablet, phone).

It ensures usability and readability across all screens.



🧩 Key Concepts

Concept	Description

Viewport	Controls visible area of a webpage
Media Queries	Apply styles based on screen size
Flexbox / Grid	Layout systems for arranging elements
Relative Units	Use %, em, rem, vh, vw instead of fixed pixels



---

🧱 Basic Example with Media Query

<!DOCTYPE html>
<html>
<head>
  <style>
    body {
      font-family: Arial;
      margin: 0;
    }

    .container {
      display: flex;
      flex-direction: row;
    }

    .box {
      flex: 1;
      padding: 20px;
      text-align: center;
    }

    .box:nth-child(1) { background: lightcoral; }
    .box:nth-child(2) { background: lightseagreen; }
    .box:nth-child(3) { background: lightblue; }

    /* Responsive layout */
    @media (max-width: 600px) {
      .container {
        flex-direction: column;
      }
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="box">Box 1</div>
    <div class="box">Box 2</div>
    <div class="box">Box 3</div>
  </div>
</body>
</html>

Explanation:
👉 When the screen width becomes 600px or smaller, boxes stack vertically.


---

📱 Viewport Tag

Add this inside <head> for proper scaling:

<meta name="viewport" content="width=device-width, initial-scale=1.0">


---

🎯 

Always test your layout using browser’s responsive mode (F12 → Device Toolbar).

Practice designing first for mobile, then adjust for larger screens — that’s called mobile-first design.

