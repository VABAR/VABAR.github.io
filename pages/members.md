---
layout: page-fullwidth
title: "Members"
subheadline: "The people behind the group"
show_meta: false
permalink: "/members/"
---

{% for inst in site.data.institutions %}
  {% capture ninstitutions %}{{ forloop.length }}{% endcapture %}
{% endfor %}

{% for inst in site.data.members %}
  {% capture nmembers %}{{ forloop.length }}{% endcapture %}
{% endfor %}

Counting {{ nmembers }} individuals from {{ ninstitutions }} institutions in 5 different countries

<div class="row">
  {% for member in site.data.members %}
	{% if member.group == "pi" %}
		<div class="medium-6 large-4 columns">
			<div class="row">
		<!--          <li>-->
			{% if member.img %}
				<a href="{{ member.url }}">
					<img src="{{ site.url }}/images/members/{{ member.img }}">
				</a>
			{% else %}
				&nbsp;
			{% endif %}
				<br/>
				<a href="{{ member.url }}">
				{{ member.name }}
				</a>
				<p>
				{{ member.position }}<br>
				{% for institution in site.data.institutions %}
					{% if institution.name == member.affiliation %}
						<a href="{{ institution.url }}">
							{{ institution.title }}
						</a>
					{% endif %}
				{% endfor %}
				</p>
		<!--          </li>-->
			</div><!-- /.row -->
		</div><!-- /.column -->
	{% endif %}
  {% endfor %}
</div><!-- /.row -->

<div class="row">
  {% for member in site.data.members %}
	{% if member.group == "member" %}
		<div class="medium-6 large-4 columns">
			<div class="row">
		<!--          <li>-->
			{% if member.img %}
				<a href="{{ member.url }}">
					<img src="{{ site.url }}/images/members/{{ member.img }}">
				</a>
			{% else %}
				&nbsp;
			{% endif %}
				<br/>
				<a href="{{ member.url }}">
				{{ member.name }}
				</a>
				<p>
				{{ member.position }}<br>
				{% for institution in site.data.institutions %}
					{% if institution.name == member.affiliation %}
						<a href="{{ institution.url }}">
							{{ institution.title }}
						</a>
					{% endif %}
				{% endfor %}
				</p>
		<!--          </li>-->
			</div><!-- /.row -->
		</div><!-- /.column -->
	{% endif %}
  {% endfor %}
</div><!-- /.row -->

<div class="row">
  {% for member in site.data.members %}
	{% if member.group == "student" %}
		<div class="medium-6 large-4 columns">
			<div class="row">
		<!--          <li>-->
			{% if member.img %}
				<a href="{{ member.url }}">
					<img src="{{ site.url }}/images/members/{{ member.img }}">
				</a>
			{% else %}
				&nbsp;
			{% endif %}
				<br/>
				<a href="{{ member.url }}">
				{{ member.name }}
				</a>
				<p>
				{{ member.position }}<br>
				{% for institution in site.data.institutions %}
					{% if institution.name == member.affiliation %}
						<a href="{{ institution.url }}">
							{{ institution.title }}
						</a>
					{% endif %}
				{% endfor %}
				</p>
		<!--          </li>-->
			</div><!-- /.row -->
		</div><!-- /.column -->
	{% endif %}
  {% endfor %}
</div><!-- /.row -->

<hr> 

<div class="row">
  {% for institution in site.data.institutions %}
    <div class="medium-4 large-3 columns">
      <a href="{{ institution.url }}">
        <img class="t30 b15" src="{{ site.url }}/images/institutions/{{ institution.logo }}">
      </a>
      {% if institution.logo_has_title != true %}
        <p>
          <a href="{{ institution.url }}">{{ institution.title }}</a>
        </p>
      {% endif %}
    </div><!-- /.medium-6.columns -->
  {% endfor %}
</div><!-- /.row -->

