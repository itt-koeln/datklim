---
# Feel free to add content and custom Front Matter to this file.
title: Landingpage
layout: home
nav_exclude: true
---
# DatKlim

<div class="dropdown">
 <button class="dropdown-trigger btn btn-primary" onclick= "toggleDropdown()">Cluster 1: Basic Knowledge and Data Competence</button>
 <ul class="dropdown-menu">
    <li><a href ="#"> Cluster 1 </a>
        <table>
            <tr>
                <td>Content </td>
                <td> Question </td>
            </tr>
            <tr>
                <td> Introduction </td>
                <td> What: This learning units aims to provide general  insights  into  the  use,  the  quality and the sources of data  How:  Showing  the  relevance  of  data  for      climate change; providing relevant databases and tools Why: Enabling the learner to  understand the common use of data, since the reliability,  availability  and  accessibility  of various data sources is increasing,  </td>
            </tr>
        </table>
    </li>
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