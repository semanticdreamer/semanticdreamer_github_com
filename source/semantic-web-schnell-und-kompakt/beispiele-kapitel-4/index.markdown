---
layout: page
title: "Semantic Web schnell+kompakt Beispiele Kapitel 4"
comments: true
sharing: true
footer: true
---
<h2>Listing 4.1 Linux/ Unix/ OSX Command Line Beispiel für Paget Subversion Export</h2>
{% codeblock Linux/ Unix/ OSX Command Line Beispiel für Paget Subversion Export [lang:bash] %}
cd $PROJECT_HOME && svn export -r 61 http://paget.googlecode.com/svn/trunk ./lib/paget
{% endcodeblock %}

<h2>Listing 4.2 Linux/ Unix/ OSX Command Line Beispiel für Moriarty Subversion Export</h2>
{% codeblock Linux/ Unix/ OSX Command Line Beispiel für Moriarty Subversion Export [lang:bash] %}
cd $PROJECT_HOME && svn export -r 62 http://moriarty.googlecode.com/svn/trunk/ ./lib/moriarty
{% endcodeblock %}

<h2>Listing 4.3 Beschreibung der Ressource http://localhost/id/me</h2>
{% include_code Beschreibung der Ressource http://localhost/id/me sw-sk-beispiele/paget/~james/id/me.rdf lang:xml %}