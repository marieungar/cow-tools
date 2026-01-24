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
<!-- Dropdown wrapper -->
<span class="dropdown-wrapper">
  <a href="#" id="more-link-2"><i>Bio</i></a>
  <span id="dropdown-2">
    Cow Tools found her roots helping organize underground forest parties while living in the UK. Now based in NYC, she's played venues like Bossa Nova Civic Club and Below Grūnd. She gravitates toward hardgroove, hypnotic, and minimal techno, blending resonant basslines and ethereal textures. Also a writer, she finds particular delight in crafting a sense of narrative arc in her sets.
  </span>
</span>
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
  /* Video dropdown */
  #dropdown {
    display: none;      /* hidden until clicked */
    margin-left: 40px;  /* old-school indent */
    margin-top: 5px;    /* small gap below the "Video" link */
  }

  #dropdown a {
    display: block;     /* each dropdown link on its own line */
    margin: 6px 0;      /* spacing between dropdown links */
    font-style: italic; /* old-timey italic style */
  }

  /* Bio dropdown */
  #dropdown-2 {
    display: none;      /* hidden until clicked */
    margin-left: 40px;  /* match Video dropdown */
    margin-top: 5px;    /* small gap below the "Bio" link */
    text-align: justify;  /* justify the paragraph text */
  }

  /* Wrapper spacing and no extra blank space */
  .dropdown-wrapper {
    display: block;     /* behaves like a block */
    line-height: 1;
    margin: 0;
  }

  /* Make links block-level */
  #more-link,
  #more-link-2 {
    display: block;
    margin-left: 0;
    margin-top: 4px;
    margin-bottom: 4px;
  }
</style>



<!-- JavaScript goes here -->
<script>
document.addEventListener("DOMContentLoaded", function () {
  const dropdowns = [
    { linkId: "more-link", menuId: "dropdown" },
    { linkId: "more-link-2", menuId: "dropdown-2" }
  ];

  dropdowns.forEach(item => {
    const link = document.getElementById(item.linkId);
    const menu = document.getElementById(item.menuId);

    link.addEventListener("click", function (e) {
      e.preventDefault();
      menu.style.display =
        menu.style.display === "none" ? "block" : "none";
    });
  });
});
</script>
