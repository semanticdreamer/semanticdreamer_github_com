---
layout: page
title: "Semantic Web schnell + kompakt Beispiele Kapitel 3"
comments: true
sharing: true
footer: true
---
<h2>RDFS Eigenschaften</h2>
<h3>rdfs:subClassOf</h3>
{% include_code rdfs:subClassOf sw-sk-beispiele/Kapitel3/RDFS-subClassOf.turtle lang:text %}
<h3>rdfs:subPropertyOf</h3>
{% include_code rdfs:subPropertyOf sw-sk-beispiele/Kapitel3/RDFS-subPropertyOf.turtle lang:text %}
<h3>rdfs:range und rdfs:domain</h3>
{% include_code rdfs:range und rdfs:domain sw-sk-beispiele/Kapitel3/RDFS-range+domain.turtle lang:text %}
<h3>rdfs:label und rdfs:comment</h3>
<p>Quelle: gekürzt aus <a href="http://xmlns.com/foaf/spec/index.rdf">FOAF Vokabular Spezifikation 0.91</a></p>
{% include_code rdfs:label und rdfs:comment sw-sk-beispiele/Kapitel3/RDFS-label+comment.rdf lang:xml %}
<h3>rdfs:type</h3>
{% include_code rdfs:type sw-sk-beispiele/Kapitel3/RDFS-type.rdf lang:xml %}

<h2>RDFS Hilfseigenschaften</h2>
<h3>rdfs:seeAlso</h3>
{% include_code rdfs:seeAlso sw-sk-beispiele/Kapitel3/RDFS-seeAlso.rdf lang:xml %}
<h3>rdfs:isDefinedBy</h3>
<p>Quelle: gekürzt aus <a href="http://xmlns.com/foaf/spec/index.rdf">FOAF Vokabular Spezifikation 0.91</a></p>
{% include_code rdfs:isDefinedBy sw-sk-beispiele/Kapitel3/RDFS-isDefinedBy.rdf lang:xml %}

<h2>Listing 3.1 Beispiel des Kopf eines OWL-Dokumentes (gekürzt)</h2>
{% include_code Beispiel des Kopf eines OWL-Dokumentes (gekürzt) sw-sk-beispiele/Kapitel3/kap03_01.owl lang:xml %}

<h2>Listing 3.2 Einfaches SPARQL Beispiel</h2>
{% include_code Einfaches SPARQL Beispiel sw-sk-beispiele/Kapitel3/kap03_02.sparql lang:text %}

<h2>Listing 3.3 Erweitertes SPARQL Beispiel</h2>
{% include_code Erweitertes SPARQL Beispiel sw-sk-beispiele/Kapitel3/kap03_03.sparql lang:text %}