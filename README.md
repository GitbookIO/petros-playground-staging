# Page 1

{% swagger method="get" path="/versions" baseUrl="https://something.com/api/v1" summary="versions" %}
{% swagger-description %}
Something
{% endswagger-description %}

{% swagger-parameter in="path" %}

{% endswagger-parameter %}

{% swagger-response status="200: OK" description="Test" %}
```javascript
{
    something: 1
}
```


{% endswagger-response %}
{% endswagger %}
