---
layout: default
title: News
---

<div class="col-12 col-sm-12 col-lg-12">

    {% assign news = site.data.news.news | sort:"date" %}
    {% for n in news reversed %}

	<div class="col-12 col-sm-12 col-lg-12">
	<a name="{{ n.date }}"></a><h2>{{ n.title }}<br><small>{{ n.date }}</small></h2>
	<p>{{ n.text }}</p>
	</div>

	{% endfor %}

</div><!--/span-->
