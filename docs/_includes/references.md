{% for section in site.data.references.section %}

{% for reference in section.references %}

[{{ reference.name }}]: {{ reference.url }} "{{ reference.citation }}"

{% endfor %}

{% endfor %}
