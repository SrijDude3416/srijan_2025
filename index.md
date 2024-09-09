---
layout: page
title: Srijan - Home 
description: Home Page
hide: true
---

<!-- Include submenu from _includes to top of pages -->
{% include nav/home.html %}

<style>

.typewriter h1 {
  overflow: hidden; /* Ensures the content is not revealed until the animation */
  font-family: Monospace;
  border-right: .015em solid orange; /* The typwriter cursor */
  white-space: nowrap; /* Keeps the content on a single line */
  margin: 0 auto; /* Gives that scrolling effect as the typing happens */
  letter-spacing: 0.015em; /* Adjust as needed */
  animation: 
    typing 15.0s steps(30, end) forwards,
    blink-caret 1s step-end infinite;
  animation-delay: 0ms;
  animation-fill-mode: both;
  color: #FFFFFF
}

/* The typing effect */
@keyframes typing {
  0% {
    width: 0;
  }
  25%, 50%, 75% {
    width: 100%;
  }
  100% {
    width: 100%;
  }
}
/* The typewriter cursor effect */
@keyframes blink-caret {
  from, to { border-color: transparent }
  50% { border-color: white; }
}

h2 {
    color: #FFFFEE;
}

h1 {
  color: #FFFFFF
}

h1:hover {
  font-size: 32px;
}
</style>

<script>
  document.addEventListener("DOMContentLoaded", function() {
  setTimeout(function() {
      document.querySelector("body").classList.add("loaded");
  }, 2000)
});
</script>

<!-- <script>
document.addEventListener("DOMContentLoaded", function() {
  const words = ["Welcome", "to", "Srijan's", "Blog"];
  let wordIndex = 0;
  
  function updateWord() {
    const titleElement = document.querySelector(".typewriter h1");
    titleElement.textContent = words[wordIndex];
    wordIndex = (wordIndex + 1) % words.length;
  }

  setInterval(updateWord, 1); // Change word every 3.5 seconds
});
</script> -->

<div class="typewriter">
    <h1>Welcome to Srijan's Blog</h1>
</div>

<br>

## Hi I'm Srijan!

### If you're new here, feel free to check out my [LinkedIn](https://www.linkedin.com/in/srijan-atti-213918273/) 

### Learn a bit [about me](/srijan_2025/about/)

### Or browse a few of the many projects I've created:
### [Algorithms Compare](/srijan_2025/algorithm)
![](images/algorithmsCompare.png)