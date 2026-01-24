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
<!-- Dropdown wrapper -->
<div class="dropdown-wrapper">
  <a href="#" id="more-link"><i>Video</i></a>
  <div id="dropdown">
    <a href="https://www.youtube.com/watch?v=E9lYTVaFHeU" target="_blank"><i>Cow Tools @ Motion Studies</i></a>
  </div>
</div>
<a href="mailto:cow.tools.dj@gmail.com"><i>E-Mail</i></a>
<br>
<a href="https://www.instagram.com/cow.tools.cow.tools" target="_blank"><i>Instagram</i></a>



<!-- CSS for dropdown -->
<style>
  /* Hide dropdown by default */
  #dropdown {
  display: none;      /* hide by default */
  margin-left: 20px;  /* a bit more old-school indent */
  margin-top: 5px;    /* small gap from the link */
  }

  #dropdown a {
  display: block;
  margin: 4px 0;
  font-style: italic;  /* matches your <i> style, optional */
  }

  /* Wrapper spacing and no extra blank space */
  .dropdown-wrapper {
    line-height: 1; /* collapse extra vertical space */
    margin-bottom: 0;
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