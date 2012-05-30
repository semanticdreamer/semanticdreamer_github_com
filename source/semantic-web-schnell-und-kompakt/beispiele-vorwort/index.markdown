---
layout: page
title: "Semantic Web schnell + kompakt Beispiele Vorwort"
comments: true
sharing: true
footer: true
---

<h2>Beispiel: SPARQL-Anfrage</h2>
{% include_code SPARQL: "Wie heißt die Ehefrau von Helmut Schmidt?" sw-sk-beispiele/Vorwort/vor00_01.sparql lang:text %}

<h2>Beispiel: DBpedia SPARQL-Anfrage</h2>
<p>
	SPARQL Endpunkt (<a href="http://www.openlinksw.com/" title="openlinksw.com">OpenLink Virtuoso</a> SPARQL Query): <a href="http://dbpedia.org/sparql?default-graph-uri=http%3A%2F%2Fdbpedia.org&amp;should-sponge=&amp;query=PREFIX+dbpedia%3A+%3Chttp%3A%2F%2Fdbpedia.org%2Fresource%2F%3E%0D%0APREFIX+dbpprop%3A+%3Chttp%3A%2F%2Fdbpedia.org%2Fproperty%2F%3E%0D%0ASELECT+%3Fname%0D%0AWHERE+%7B%0D%0A++dbpedia%3AHelmut_Schmidt+dbpprop%3Aspouse+%3Fname%0D%0A%7D&amp;format=text%2Fhtml&amp;debug=on">http://dbpedia.org/sparql</a>
</p>
<p>
	SPARQL Explorer: <a href="http://dbpedia.org/snorql/?query=PREFIX+dbpedia%3A+%3Chttp%3A%2F%2Fdbpedia.org%2Fresource%2F%3E%0D%0APREFIX+dbpprop%3A+%3Chttp%3A%2F%2Fdbpedia.org%2Fproperty%2F%3E%0D%0ASELECT+%3Fname%0D%0AWHERE+%7B%0D%0A++dbpedia%3AHelmut_Schmidt+dbpprop%3Aspouse+%3Fname%0D%0A%7D">http://dbpedia.org/snorql</a>
</p>
