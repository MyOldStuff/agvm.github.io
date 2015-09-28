---
author: x
date: 2012-11-02 12:00:44+00:00
layout: page
slug: speiseplan
title: Speiseplan
wordpress_id: 1142
mo:
  datum: 21. September
  vorspeise: Käserahmsuppe 
  heuptgericht: Risotto mit Kürbis und Erbsen
  nachspeisse: 
di:
  datum: 22. September
  vorspeise:  
  heuptgericht: Paprikagulasch vom Schwein mit Butternudeln
  nachspeisse: Milchreis 
mi:
  datum: 23. September
  vorspeise: Kürbisrahmsuppe 
  heuptgericht: Putenschnitzel in Schwammerlsauce mit Spätzle
  nachspeisse:  
do:
  datum: 24. September
  vorspeise:  
  heuptgericht: Rinderbraten mit Blaukraut und Semmelknödel
  nachspeisse: Vanillepudding mit Himbeeren 
fr:
  datum: 25. September
  vorspeise: Broccolirahmsuppe 
  heuptgericht: Rahmspinat mit Spiegelei und Röstkartoffeln
  nachspeisse:  
---

## Montag, {{ page.mo.datum }}
<pre>
{% if page.mo.vorspeise %}
{{ page.mo.vorspeise }}
***
{% endif %}{% if page.mo.heuptgericht %}
{{ page.mo.heuptgericht }}
{% endif %}{% if page.mo.nachspeisse %}
***
{{ page.mo.nachspeisse }}
{% endif %}
</pre>

## Dienstag, {{ page.di.datum }}
<pre>
{% if page.di.vorspeise %}
{{ page.di.vorspeise }}
***
{% endif %}{% if page.di.heuptgericht %}
{{ page.di.heuptgericht }}
{% endif %}{% if page.di.nachspeisse %}
***
{{ page.di.nachspeisse }}
{% endif %}
</pre>

## Mittwoch, {{ page.mi.datum }}
<pre>
{% if page.mi.vorspeise %}
{{ page.mi.vorspeise }}
***
{% endif %}{% if page.mi.heuptgericht %}
{{ page.mi.heuptgericht }}
{% endif %}{% if page.mi.nachspeisse %}
***
{{ page.mi.nachspeisse }}
{% endif %}
</pre>

## Donnerstag, {{ page.do.datum }}
<pre>
{% if page.do.vorspeise %}
{{ page.do.vorspeise }}
***
{% endif %}{% if page.do.heuptgericht %}
{{ page.do.heuptgericht }}
{% endif %}{% if page.do.nachspeisse %}
***
{{ page.do.nachspeisse }}
{% endif %}
</pre>

## Freitag, {{ page.fr.datum }}
<pre>
{% if page.fr.vorspeise %}
{{ page.fr.vorspeise }}
***
{% endif %}{% if page.fr.heuptgericht %}
{{ page.fr.heuptgericht }}
{% endif %}{% if page.fr.nachspeisse %}
***
{{ page.fr.nachspeisse }}
{% endif %}
</pre>
