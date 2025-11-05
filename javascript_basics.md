What is JavaScript?

JavaScript (JS) is the programming language of the web.
It makes websites interactive and dynamic — anything that moves, updates, or reacts on a webpage is powered by JS.


---

🧩 How to Add JavaScript

1. Inline

<button onclick="alert('Hello!')">Click Me</button>


2. Internal

<script>
  alert("Welcome to JavaScript!");
</script>


3. External

<script src="script.js"></script>




---

🧱 Basic Syntax

// Variables
let name = "John";
const age = 25;

// Functions
function greet() {
  console.log("Hello, " + name);
}
greet();

// Conditional Statements
if (age >= 18) {
  console.log("You are an adult!");
}

// Loops
for (let i = 1; i <= 5; i++) {
  console.log("Number " + i);
}

Explanation:

let & const → variable declarations

function → reusable block of code

if → decision-making

for → repeat actions



---

🖱️ DOM Manipulation

DOM (Document Object Model) lets JS interact with HTML elements.

<h2 id="title">Welcome</h2>
<button onclick="changeText()">Change Title</button>

<script>
  function changeText() {
    document.getElementById("title").innerHTML = "Hello, JavaScript!";
  }
</script>

➡️ This script changes the heading when the button is clicked.


---

🧠 Mini Exercise

Try making a simple counter:

<h2 id="count">0</h2>
<button onclick="increase()">+</button>
<button onclick="reset()">Reset</button>

<script>
let num = 0;

function increase() {
  num++;
  document.getElementById("count").innerText = num;
}

function reset() {
  num = 0;
  document.getElementById("count").innerText = num;
}
</script>
