---
title: "Publications"
layout: gridlay
sitemap: false
permalink: /publications/
years: [2006, 2007, 2008, 2009, 2010, 2011, 2012, 2013, 2014, 2015, 2016, 2017, 2018, 2019, 2020, 2021, 2022, 2023, 2024, 2025]
---

<style>
.jumbotron{
    padding:3%;
    padding-bottom:10px;
    padding-top:10px;
    margin-top:10px;
    margin-bottom:30px;
}
</style>

<div class="jumbotron">
### Books
{% bibliography --query @Book %}
</div>

<div class="jumbotron">
### Book Chapter
{% bibliography --query @InBook %}
</div>

<div class="jumbotron">
### Journal Articles
{% bibliography --query @article %}
</div>

<div class="jumbotron">
### Conference Proceedings
{% bibliography --query @inproceedings %}
</div>

<div class="jumbotron">
### In Collections
{% bibliography --query @incollection %}
</div>

<div class="jumbotron">
### Technical Reports {% bibliography --query @TechReport %}
</div>
