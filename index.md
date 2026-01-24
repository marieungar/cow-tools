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
<span class="dropdown-wrapper">
  <a href="#" id="more-link"><i>Video</i></a>
  <span id="dropdown">
    <a href="https://www.youtube.com/watch?v=E9lYTVaFHeU" target="_blank">Cow Tools @ Motion Studies</a>
  </span>
</span>
<a href="mailto:cow.tools.dj@gmail.com"><i>E-Mail</i></a>
<br>
<a href="https://www.instagram.com/cow.tools.cow.tools" target="_blank"><i>Instagram</i></a>

<!-- CSS for dropdown -->
<style>
  /* Hide dropdown by default */
  #dropdown {
    display: none;      /* hidden until clicked */
    margin-left: 20px;  /* old-school indent */
    margin-top: 5px;    /* small gap below the "Video" link */
  }

  #dropdown a {
    display: block;     /* each dropdown link on its own line */
    margin: 4px 0;      /* spacing between dropdown links */
    font-style: italic; /* old-timey italic style */
  }

  /* Wrapper spacing and no extra blank space */
  .dropdown-wrapper {
    display: block;     /* behaves like a block, but no default div spacing */
    line-height: 1;     /* collapse extra vertical space */
    margin: 0;          /* remove any default margin */
  }

  /* Make the "Video" link block-level */
  #more-link {
    display: block;
    margin-left:0px;
    margin-top: 4px;
    margin-bottom: 4px;         
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