---
title: Datasets
category: resource
layout: default
---

## Datasets

{% capture census %}{% include_relative content/datasets/census.md %}{% endcapture %}
{{ census | markdownify }}

{% capture imd %}{% include_relative content/datasets/imd.md %}{% endcapture %}
{{ imd | markdownify }}

{% capture osgeo %}{% include_relative content/datasets/os_geodatapack.md %}{% endcapture %}
{{ osgeo | markdownify }}

{% capture js %}{% include_relative content/datasets/jsnow.md %}{% endcapture %}
{{ js | markdownify }}

{% capture abb %}{% include_relative content/datasets/airbnb.md %}{% endcapture %}
{{ abb | markdownify }}

{% capture tweets %}{% include_relative content/datasets/twitter.md %}{% endcapture %}
{{ tweets | markdownify }}


