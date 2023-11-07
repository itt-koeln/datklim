---
# Feel free to add content and custom Front Matter to this file.
title: Landingpage
layout: home
nav_exclude: true
---
# Holi

<div class="dropdown">
 <button class="dropdown-trigger btn btn-primary">Dropdown Button</button>
 <ul class="dropdown-menu">
    <li><a href="#">Menu Item 1</a></li>
    <li><a href="#">Menu Item 2</a></li>
    <li><a href="#">Menu Item 3</a></li>
 </ul>
</div>


<script>
  function toggleDropdown() {
    var menu = document.getElementById("menu");
    if (menu.style.display === "none" || menu.style.display === "") {
      menu.style.display = "block";
    } else {
      menu.style.display = "none";
    }
  }
</script>