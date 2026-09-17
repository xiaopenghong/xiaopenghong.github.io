---
title: Team
permalink: /team/
redirect_from:
  - /student/
layout: section
kicker: People / Team
intro: Faculty, students, and alumni of the research team.
---

{% for group in site.data.team.groups %}
<section class="team-group{% if group.id == 'faculty' %} team-group--faculty{% endif %}" id="{{ group.id }}" aria-labelledby="{{ group.id }}-title">
  <div class="team-group__heading">
    <h2 id="{{ group.id }}-title">{{ group.title }}</h2>
    <span class="team-group__count">{{ group.members.size }} {% if group.members.size == 1 %}person{% else %}people{% endif %}</span>
  </div>
  <div class="team-grid">
    {% for member in group.members %}
    <article class="team-card">
      <div class="team-card__portrait">
        {% if member.photo %}
        <img src="{{ '/assets/images/team/' | append: member.photo | relative_url }}" alt="Portrait of {{ member.name | escape }}" loading="lazy">
        {% else %}
        <span class="team-card__initial" aria-hidden="true">{{ member.name | slice: 0 }}</span>
        {% endif %}
      </div>
      <div class="team-card__details">
        <h3>{{ member.name }}</h3>
        {% if member.role %}<p class="team-card__role">{{ member.role }}</p>{% endif %}
        {% if member.bio %}<p class="team-card__bio">{{ member.bio }}</p>{% endif %}
        {% if member.note %}<p class="team-card__note">{{ member.note }}</p>{% endif %}
        {% if member.website or member.scholar %}
        <div class="team-card__links">
          {% if member.website %}<a href="{{ member.website }}">Website</a>{% endif %}
          {% if member.scholar %}<a href="{{ member.scholar }}">Google Scholar</a>{% endif %}
        </div>
        {% endif %}
      </div>
    </article>
    {% endfor %}
  </div>
</section>
{% endfor %}

<section class="team-join" aria-labelledby="team-join-title">
  <h2 id="team-join-title">Join the team</h2>
  <p>We welcome inquiries from students interested in computer vision, multimodal learning, and continual learning. Please share your research interests and relevant experience when you <a href="{{ '/contact/' | relative_url }}">contact us</a>.</p>
</section>
