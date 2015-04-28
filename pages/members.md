---
layout: page
title: "Members"
subheadline: "The people behind the group"
show_meta: false
permalink: "/members/"
---

<div class="row">
  {% for institution in site.data.institutions %}
    <div class="medium-6 columns">
      <a href="{{ institution.url }}">
        <img class="t30" src="{{ site.url }}/images/institutions/{{ institution.logo }}">
      </a>
      <p>
        <a href="{{ institution.url }}">{{ institution.title }}</a>
      </p>
      
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

