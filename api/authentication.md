# Authentication

API authentication is done via access tokens, access tokens can be issued in a couple ways:

* By authenticating via username and password \(only allowed for the website\)
* User or organization issued access tokens

Getting tokens via OAuth2 will be another authentication method offered in the future.

Authentication is only required for modifying and creating snippets and accounts.

To create an access token either go to your user settings or to the settings for your organization, go to the access section and create a new token.

Tokens are supplied via the Authorization header as a bearer token. 

{% api-method method="post" host="/snippets" path="" %}
{% api-method-summary %}
Authentication Example
{% endapi-method-summary %}

{% api-method-description %}

{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-headers %}
{% api-method-parameter name="Authorization" type="string" required=true %}
Bearer &lt;token goes here&gt;
{% endapi-method-parameter %}
{% endapi-method-headers %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=401 %}
{% api-method-response-example-description %}
You didn't provide authentication or the provided authentication failed.
{% endapi-method-response-example-description %}

```

```
{% endapi-method-response-example %}

{% api-method-response-example httpCode=403 %}
{% api-method-response-example-description %}
The user that the authentication was issued to doesn't have access to the requested resource.
{% endapi-method-response-example-description %}

```

```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

