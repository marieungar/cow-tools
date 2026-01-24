---
layout: default
---

<br>
<br>
<br>
Cow Tools is a DJ based in Brooklyn.
<br>
<br>
<br>
<a href="https://ra.co/dj/cowtools" target="_blank"><i>RA</i></a>
<br>
<a href="https://www.soundcloud.com/cow-tools-cow-tools/tracks" target="_blank"><i>Mixes</i></a>
<br>
<a href="#" id="more-link"><i>Videos</i></a>
<div id="dropdown">
  <a href="https://www.youtube.com/watch?v=E9lYTVaFHeU" target="_blank"><i>Cow Tools @ Motion Studies</i></a>
</div>
<a href="mailto:cow.tools.dj@gmail.com"><i>E-Mail</i></a>
<br>
<a href="https://www.instagram.com/cow.tools.cow.tools" target="_blank"><i>Instagram</i></a>


<!-- style for the dropdown -->
<style>
  #dropdown {
    display: none;       /* hidden by default */
    margin-left: 10px;   /* indent to match your current layout */
  }

  #dropdown a {
    display: block;      /* each link takes full line */
    margin: 3px 0;       /* optional spacing between links */
  }
</style>


<!-- JavaScript goes here -->
<script>
document.addEventListener("DOMContentLoaded", function () {
  const link = document.getElementById("more-link");
  const dropdown = document.getElementById("dropdown");

  link.addEventListener("click", function (e) {
    e.preventDefault();
    dropdown.style.display =
      dropdown.style.display === "none" ? "block" : "none";
  });
});
</script>