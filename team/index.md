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
  filters="role: phd"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: master"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: undergrad"
%}

{% include section.html %}

## Alumni

{%
  include list.html
  data="members"
  component="portrait"
  filters="role: alumni"
%}
{:.center}
