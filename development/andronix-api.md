# Andronix API

{% api-method method="get" host="https://api.andronix.app" path="/get/distro/commands" %}
{% api-method-summary %}

{% endapi-method-summary %}

{% api-method-description %}

{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-body-parameters %}
{% api-method-parameter name="api\_key" type="string" required=true %}
Your API key. Details to get your API key are here.
{% endapi-method-parameter %}

{% api-method-parameter name="distro" type="string" required=true %}
ID of the distro you're trying to fetch commands for. Get all the IDs here.
{% endapi-method-parameter %}
{% endapi-method-body-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}
This carries the command to install the passed Distro. **This doesn't include a Desktop Environment.**
{% endapi-method-response-example-description %}

```

```
{% endapi-method-response-example %}

{% api-method-response-example httpCode=404 %}
{% api-method-response-example-description %}
Could not find a cake matching this query.
{% endapi-method-response-example-description %}

```
{    "message": "Ain't no cake like that."}
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

