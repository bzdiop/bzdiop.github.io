---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<script>
function button(id) {
  var x = document.getElementById(id);
  var ids = ["abs1", "pres1", "abs2", "pres2", "abs3", "pres3", "abs4", "pres4" ];
  for(var i = 0; i < ids.length; i++) {
    var item = ids[i];
    if (item != id) {
      document.getElementById(item).style.display = "none";
    } else {
      if (x.style.display === "none") {
        x.style.display = "block"
      } else {
        x.style.display = "none";
      }
    }
  }	
}
</script> 

<head>
<style>
.button {
  border: black ; /*none*/
  color: black;
  padding: 5px 5px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 12px;
  margin: 1px 1px;
  cursor: pointer;
}

.button1 {background-color: #4CAF50;border-radius: 12px;} /* Green */
.button2 {background-color: #008CBA;border-radius: 12px;} /* Blue */
.button3 {background-color: none: 12px;border-radius: 12px;} /* Light Gray */
.button4 {background-color: #969696;border-radius: 12px;} /* Gray */

div {
  text-align: justify;
  text-justify: inter-word;
}
</style>
</head>

<!-- ## About me -->

I am a PhD candidate at the Department of Economics of the University of Oxford. My research is in applied microeconomics, with a focus on health and migrations. I am interested in understanding the factors --- frictions and preferences --- that influence individuals' decision to relocate within a country.  

<!-- I am the T.A for the Quantitative Methods course of Oxford's MSc. in Economics for Development and co-organized the 2021 conference on "machine learning and economic inequality", hosted by [Maximilian Kasy](https://maxkasy.github.io/home/).  

I will be co-hosting (with Max) on June 20, 2022 the Machine Learning and Economics day at the Department of Economics' [Research Jamboree 2022](https://www.economics.ox.ac.uk/research-jamboree-2022). Find the [program here](https://maxkasy.github.io/home/ML_Econ_Oxford/Jamboree_2022/).  

Previously, I worked as a research staff at the [University of Chicago Urban Labs](https://urbanlabs.uchicago.edu/), and at [gui2de](https://gui2de.georgetown.edu/#). You can find an excerpt of my [CV here](https://bzdiop.github.io/cv/).--> 
