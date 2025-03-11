// Get the heading element
var heading = document.getElementById("heading");

// Add an event listener to the heading
heading.addEventListener("click", function() {
  // Change the text color to red
  heading.style.color = "red";
});

// Get the paragraph element
var paragraph = document.getElementById("paragraph");

// Add an event listener to the paragraph
paragraph.addEventListener("mouseover", function() {
  // Change the font size to 24px
  paragraph.style.fontSize = "24px";
});

paragraph.addEventListener("mouseout", function() {
  // Change the font size back to 18px
  paragraph.style.fontSize = "18px";}
