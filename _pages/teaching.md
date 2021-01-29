---
layout: page
title: teaching
permalink: /teaching/
#description: Courses.
---
<h3>PhD Students</h3>
<ul>
     <li>
    William Grison (2020-2023) : «Dialogue explicatif pour l’interprétation de scènes visuelles.» Co-encadrement avec Michel Crucianu et Nicolas Thome (CNAM).
	</li>
    <li>
    Alexis Lechat (2018-2021) : «Apprentissage incrémental pour systèmes de question réponse visuels. » Co-encadrement avec Frédéric Jurie (Univ. De Caen/GREYC).
	</li>
     <li>
    Maxime Bucher (2015-2018) : «Modélisation par attributs pour la reconnaissance fine d'objets ou d'événements et données d'apprentissage rares. » Co-encadrement avec Frédéric Jurie (Univ. De Caen/GREYC).
	</li>
    <li>
    Isabelle Leang (2013-2016) : « Vision attentionnelle pour l'interprétation sémantique de scènes dynamiques. » Co-encadrement avec Jacques Droulez (CNRS/UPMC/ISIR) et Benoît Girard (CNRS/UPMC/ISIR).
	</li>
    <li> 
    Cédric Le Barz (2012-2015) : « Navigation visuelle pour les missions autonomes des petits drones. » Co-encadrement avec M. Sanfourche (ONERA) et M. Cord (UPMC/LIP6).
 	</li>
    <li>
    Joseph Defretin (2008-2011) : « Stratégies de vision active pour la reconnaissance et d’objets. » Co-encadrement avec G. Le Besnerais (ONERA) et N. Vayatis (ENS de Cachan / CMLA).
 	</li>
    <li>
    Christophe Guilmart (2008-2011) : « Filtrage de segments informatifs dans des vidéos ». Co-encadrement avec P. Pérez (Technicolor).
 	</li>
    <li>
    Anne-Marie Tousch (2006-2010) : « Hiérarchies sémantiques pour l’annotation multifacette d’images.» Co-encadrement avec J.-Y. Audibert (ENPC / Certis).
 	</li>
    <li>
    Jonathan Guinet (2004-2008) : « Acquisition de cible sur séquences aériennes, étude de l'apport d'informations spatio-temporelles.» Co-encadrement avec G. Le Besnerais (ONERA) et S. Philipp-Foliguet (Univ. Cergy Pontoise).
 	</li>
    <li>
    Benjamin Francesconi (2003-2007) : « Détection d’objets sur image satellitaire. »  Co-encadrement avec B. Chalmond (ENS Cachan/ Univ. Cergy Pontoise).
	</li>
</ul>
     
<h3>Courses</h3>

<h4 style="font-weight:700;"> Pattern Recognition and Machine Learning </h4>
<h5 style="color:#9999ff;"> Institut d'Optique Graduate School, 3rd year (2016, 2017, 2018, 2020, 2021) et Master ATSI Paris Saclay </h5>
<a href = "https://synapses.institutoptique.fr/catalogue/2020-2021/ue/278/9P-441-SCI-apprentissage-et-reconnaissance-de-formes"> 9P-441-SCI </a>

<!---
<ul style="list-style-type:none">
<li> Supervised learning </li>
<li> Support Vector Machines </li>
</ul>
-->

<h4 style="font-weight:700;"> Machine Learning </h4>
<h5 style="color:#9999ff;"> ENSTA ParisTech, 2nd year (2018, 2019, 2020, 2021) </h5>
<a href = "https://synapses.ensta-paris.fr/catalogue/2020-2021/ue/239/MI203-apprentissage-automatique-machine-learning"> MI203 </a>
<a href = "https://synapses.ensta-paris.fr/catalogue/2020-2021/ue/3922/MI221-introduction-a-l-apprentissage-automatique"> MI221 </a>

<!---
<ul style="list-style-type:none">
<li> Introduction </li>
<li> Elementary algorithms: kNN, naive Bayes </li>
<li> Supervised learning </li>
<li> Support Vector Machines </li>
</ul>
-->

<!---
{% for course in site.teaching %}

{% if course.redirect %}
<div class="course">
    <div class="thumbnail">
        <a href="{{ course.redirect }}" target="_blank">
        {% if course.img %}
        <img class="thumbnail" src="{{ course.img | prepend: site.baseurl | prepend: site.url }}"/>
        {% else %}
        <div class="thumbnail blankbox"></div>
        {% endif %}    
        <span>
            <h1>{{ course.title }}</h1>
            <br/>
            <p>{{ course.description }}</p>
        </span>
        </a>
    </div>
</div>
{% else %}

<div class="course">
    <div class="thumbnail">
        <a href="{{ course.url | prepend: site.baseurl | prepend: site.url }}">
        {% if course.img %}
        <img class="thumbnail" src="{{ course.img | prepend: site.baseurl | prepend: site.url }}"/>
        {% else %}
        <div class="thumbnail blankbox"></div>
        {% endif %}    
        <span>
            <h1>{{ course.title }}</h1>
            <br/>
            <p>{{ course.description }}</p>
        </span>
        </a>
    </div>
</div>

{% endif %}

{% endfor %}

-->
