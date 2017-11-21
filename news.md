---
layout: default
title: News
---

<div class="col-12 col-sm-12 col-lg-12">

    {% assign news = site.categories.news | sort:"date" %}
    {% for n in news reversed %}

	<div class="col-12 col-sm-12 col-lg-12">
    <div class="panel panel-default">
        <div class="panel-heading">
            <h2 class="panel-title">{{ n.title }}<br><small>{{ n.date | date: "%B %d, %Y" }}</small></h2>
        </div>
        <div class="panel-body">
            {{ n.content }}
        </div>
    </div>

	{% endfor %}

</div><!--/span-->
