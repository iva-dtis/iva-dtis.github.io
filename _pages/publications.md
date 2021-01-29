---
layout: page
permalink: /publications/
title: publications
description: by categories in reversed chronological order.
types: ["article","inproceedings"]
years: [2020,2018,2017,2016,2015,2014,2013,2012,2011,2010,2009,2008,2007,2006,2005,2004,2003,2002,2001,2000,1999,1998,1997,1996,1995]
---

<div id="top"></div>

<h3><a href="#journals">Journals</a> | <a href="#conferences">Conferences</a> | <a href="#chapters">Chapters</a> | <a href="#misc">Theses</a> | <a href="#misc">Misc.</a></h3>


<h3 id="journals">Journals</h3>
{% bibliography -f sh -q @article %}
<a href="#top">[top]</a>



<h3 id="conferences">Conferences</h3>
{% bibliography -f sh -q @inproceedings %}
<a href="#top">[top]</a>


<h3 id = "chapters">Chapter in book</h3>
{% bibliography -f sh -q @incollection %}
<a href="#top">[top]</a>



<h3 id="misc">Theses</h3>
{% bibliography -f sh -q @phdthesis %}
<a href="#top">[top]</a>

<h3 id="misc">Miscellaneous</h3>
{% bibliography -f sh -q @misc %}
<a href="#top">[top]</a>

