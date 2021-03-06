## Brand & Identity

### Logo

Logo iterations around brain coral pattern.

![Logo iterations](img/iterations/logo-iterations-1.2.large.png)

___

#### Mark

Logo mark exploration.

![Mark round](img/iterations/logo-mark-round-1.png)
___
Word mark exploration

![Wordmark Round](img/iterations/wordmark-round-1.png)
___
Word mark exploration around Museo Slab

![Museo Slab Wordmark](img/iterations/museo-slab-wordmark-round.png)

___

### Color

Final color palette loosely based on coral motifs.

![Palette](img/iterations/color-inventory-circles.png)

___

### Typography

Final family selection ended up being Museo, but we are making the switch over to Josefin Slab for titles.

![Type Selection](img/iterations/type-selection.png)

___

### Styleguide

{% assign componentsByType = site.components | group_by:"type" %}
{% for type in componentsByType %}
  <h3 class="sg-h2">{{ type.name | capitalize }}</h3>
  {% for entry in type.items %}
    {% include component.html %}
  {% endfor %}
{% endfor %}

#### Assets

TODO: add ppt/key templates, sketch/ai/psd files.
