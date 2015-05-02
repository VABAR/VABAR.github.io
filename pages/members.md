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

Counting {{ nmembers }} individuals from {{ ninstitutions }} institutions in 3 different countries

<div class="row">
  {% for institution in site.data.institutions %}
    <div class="medium-6 large-4 columns">
      <a href="{{ institution.url }}">
        <img class="t30" src="{{ site.url }}/images/institutions/{{ institution.logo }}">
      </a>
      {% if institution.logo_has_title != true %}
        <p>
          <a href="{{ institution.url }}">{{ institution.title }}</a>
        </p>
      {% endif %}

      <ul>
      {% for member in site.data.members %}
        {% if member.affiliation == institution.name %}
        <div class="row">
          <li>
          {% if member.img %}
            <div class="small-3 columns">
            <a href="{{ member.url }}">
              <img src="{{ site.url }}/images/members/{{ member.img }}">
            </a>
            </div><!-- /.small-3.columns -->
          {% endif %}

          <div class="small-9 columns end">
            <a href="{{ member.url }}">
              {{ member.name }}
            </a>
            <p>
              {{ member.position }}
            </p>
          </div><!-- /.small-9.columns -->
          </li>
        </div><!-- /.row -->

        {% endif %}
      {% endfor %}
      </ul>
    </div><!-- /.medium-6.columns -->
  {% endfor %}
</div><!-- /.row -->

