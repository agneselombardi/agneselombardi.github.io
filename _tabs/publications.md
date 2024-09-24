---
layout: page
icon: fas fa-archive
order: 2
---

<!--{% assign pubByYear =
    site.publications | group_by_exp:"publications", "publications.year"  | sort: "publications.year" | reverse %}-->
{% assign groups = site.publications  | group_by_exp: "publications",'publications.year' | reverse %}

{% for group in groups %}
  <h3>{{ group.name }}</h3>
  <div>
      {% assign pubs = group.items | sort: "publications.date" | reverse %}

      {% for pub in pubs %}
      	<!--<ul><li>{{ pub.authors }} ({{ pub.year}}). <em>{{ pub.title }}</em>. {{ pub.publication }}-->
        <div><i class="far fa-file-alt pub-icon"></i> {{ pub.authors }} ({{ pub.year}}). <em>{{ pub.title }}</em>. {{ pub.publication }}
    
  <div class="publinks">
    <a href="{{ pub.url_pdf }}"><i class="far fa-file-pdf"></i> PDF</a> 
    {% if pub.url_slides != '' %}
    <a href="{{ pub.url_slides }}"><i class="fab fa-slideshare"></i> Slides</a> 
    {% endif %}
    {% if pub.url_poster != '' %}
    <a href="{{ pub.url_poster }}"><i class="fab fa-slideshare"></i> Poster</a> 
    {% endif %}
    {% if pub.url_video != '' %}
    <a href="{{ pub.url_video }}"><i class="fab fa-youtube"></i> Video</a> 
    {% endif %}
  </div>
</div>
	  
      {% endfor %}</div>
    
{% endfor %}