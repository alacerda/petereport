{% load martortags %}
{% load bleach_tags %}
{{attacktree_in_finding.title | safe | bleach}}

<center>
{{attacktree_in_finding.svg_file | safe | bleach}}
</center>