# Passenger Details

{% for item in site.data.titanic %}

{{item.Name}} is {{item.Age}} years old

{% endfor %}
