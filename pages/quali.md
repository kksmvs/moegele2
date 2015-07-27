---
layout: page
title: "Qualifikation"
show_meta: false
permalink: "/qualifikation/"
header:
   image_fullwidth: "header_material.jpg"
---
<div class="row">
  <ul>
    <li><strong>frühere Leiterin der Montessori-Therapie-Fortbildung</strong></li>
    <li><strong>Montessori-Therapeutin</strong>, diplomiert durch den Montessori-Berufsverband in Zusammenarbeit mit dem Kinderzentrum München und der Ludwigs-Maximilians-Universität (LMU)   </li>
    <li><strong>Montessori-Pädagogin</strong> mit Diplomen für das Kinderhaus und die Schule ÖMG </li>
    <li><strong>AMI-Diplom</strong> (Association Montessori-International) 3 – 6 Jahre </li>
    <li><strong>Tätigkeit als Dozentin</strong> bei Fortbildungs- und Fachveranstaltungen</li>
    <li><strong>Supervision</strong> und <strong>Elternschulung</strong></li>
    <li>Vertraut mit der Deutschen <strong>Gebärdensprache</strong></li>
    <li>Mehrere Jahrzehnte <strong>Sportlehrerin</strong> an einer Schule für Kinder mit Hörschädigungen, dabei Leiterin des <strong>Schulentwicklungskonzeptes</strong></li>
	<li>Entwicklung eines Konzeptes für <strong>Sport und Bewegung in einem Senioren-Wohnstift</strong></li>
    <li><strong>Mutter</strong> von zwei erwachsenen Kindern :-)</li>

  </ul>
</div>


<ul>
    {% for post in site.categories.schwerpunkte %}
    <li><a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>