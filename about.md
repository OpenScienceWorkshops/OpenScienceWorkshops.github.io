---
layout: page
title: About Open Science Workshops
---

We want to bring open source attitudes to science! In particular we dream
about a world where it is possible to look up any scientific result, obtain
the polished article, but also obtain all the elements that went into its
production, so everything can be checked. 

Imagine being able to see the entire history of how a paper was produced,
commit by commit! Imagine being able to clone a paper, build it, and
interact with it!

This is our dream.

Members
<ul>
{% for contributor in site.github.organization_members %}
  <li>
    <img src="{{ contributor.avatar_url }}" width="32" height="32" /> <a href="{{ contributor.html_url }}">{{ contributor.login }}</a>
  </li>
{% endfor %}
</ul>

Head over to [GitHub](https://github.com/OpenScienceWorkshops) to get
involved!
