---
title: Team
nav:
  order: 2
---

# <i class="fas fa-users"></i>People

## Current Members

{%
  include list.html
  data="members"
  component="portrait"
  filters="role: lead"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: postdoc"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: programmer"
%}

{% include section.html %}

## Alumni

{%
  include list.html
  data="members"
  component="portrait"
  filters="role: phd"
%}
{:.center}
