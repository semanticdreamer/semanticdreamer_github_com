---
layout: page
title: "Semantic Web schnell + kompakt Erratum"
comments: true
sharing: true
footer: true
---

<p>Leider habe ich, trotz größter Sorgfalt, einige Fehler in meinem Buch übersehen. An dieser Stelle möchte ich die nachträglichen Korrekturen anbieten.</p>

<h2>Kapitel 4: Anhang</h2>

<dl class="erratum">
  <dt>Kapitel</dt>
  <dd>4 Anhang</dd>
  <dt>&Uuml;berschrift</dt>
  <dd>4.1  Die eigene Linked-Data-Webseite mit Paget</dd>
  <dt>Listing</dt>
  <dd><a href="http://semanticdreamer.com/semantic-web-schnell-und-kompakt/beispiele-kapitel-4/#toc-listing-4-3-beschreibung-der-ressource-httplocalhostidme">Listing 4.3: Beschreibung der Ressource http://localhost/id/me (RDF-Dokument gekürzt)</a></dd>
  <dt>Seite</dt>
  <dd>130</dd>
  <dt class="falsch">Falsch</dt>
  <dd class="falsch">
    {% codeblock lang:xml %}<foaf:homepage rdf:resource="http://jamesbond.com">{% endcodeblock %}
  </dd>
  <dt class="richtig">Richtig</dt>
  <dd class="richtig">
    {% codeblock lang:xml %}<foaf:homepage rdf:resource="http://jamesbond.com/">{% endcodeblock %}
  </dd>
</dl>
