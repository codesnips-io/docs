# Overview

## Overview

The API provides developers with a way to interact with the system. The API has full access to everything, including searching for snippets and templates, creating them, fetching them, etc.

The primary intended use of the API is for:

* Developing applications for searching and creating snippets
* Creating IDE plugins for querying and inserting snippets into files

The API is **not **intended for things like:

* Creating alternate website interfaces \(if you want more features on the official website _suggest them_\)
* Attempting to hack or brute force people's logins or any other parts of the system
* Mass automation of creating, deleting, and editing snippets \(this can result in your account being banned\)

## API Changes

The API may be changed and updated at any time. Although we'll try our best to warn developers in advance we may have to make changes at the last minute that we cannot give forewarning about.

To ensure that we can reach you when we make changes, ensure that you have marked that yourself as a developer in your account settings. When we make changes we'll send emails to all the users who have marked themselves as developers. 

{% api-method method="get" host="/" path="" %}
{% api-method-summary %}
General API Information
{% endapi-method-summary %}

{% api-method-description %}
Query for general API information
{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```
{
    "version": "1.0.0"
}
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}


