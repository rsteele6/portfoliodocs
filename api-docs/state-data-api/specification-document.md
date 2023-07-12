---
description: OpenAPI v 3.1.0
---

# Specification Document

This API allows you to retrieve and edit US State data stored in a privately-hosted MongoDB database.

All endpoints allow you to retrieve and edit various attributes about US states, such as population, nickname, and date of admission. Responses are returned in JSON.

{% swagger src="../../.gitbook/assets/states-api-spec.yaml" path="/states" method="get" fullWidth="true" %}
[states-api-spec.yaml](../../.gitbook/assets/states-api-spec.yaml)
{% endswagger %}

{% swagger src="../../.gitbook/assets/states-api-spec.yaml" path="/states/{state}" method="get" %}
[states-api-spec.yaml](../../.gitbook/assets/states-api-spec.yaml)
{% endswagger %}

{% swagger src="../../.gitbook/assets/states-api-spec.yaml" path="/states/{state}/funfact" method="get" %}
[states-api-spec.yaml](../../.gitbook/assets/states-api-spec.yaml)
{% endswagger %}

{% swagger src="../../.gitbook/assets/states-api-spec.yaml" path="/states/{state}/funfact" method="post" %}
[states-api-spec.yaml](../../.gitbook/assets/states-api-spec.yaml)
{% endswagger %}

{% swagger src="../../.gitbook/assets/states-api-spec.yaml" path="/states/{state}/funfact" method="delete" %}
[states-api-spec.yaml](../../.gitbook/assets/states-api-spec.yaml)
{% endswagger %}

{% swagger src="../../.gitbook/assets/states-api-spec.yaml" path="/states/{state}/funfact" method="patch" %}
[states-api-spec.yaml](../../.gitbook/assets/states-api-spec.yaml)
{% endswagger %}

{% swagger src="../../.gitbook/assets/states-api-spec.yaml" path="/states/{state}capital" method="get" %}
[states-api-spec.yaml](../../.gitbook/assets/states-api-spec.yaml)
{% endswagger %}

{% swagger src="../../.gitbook/assets/states-api-spec.yaml" path="/states/{state}/nickname" method="get" %}
[states-api-spec.yaml](../../.gitbook/assets/states-api-spec.yaml)
{% endswagger %}

{% swagger src="../../.gitbook/assets/states-api-spec.yaml" path="/states/{state}/population" method="get" %}
[states-api-spec.yaml](../../.gitbook/assets/states-api-spec.yaml)
{% endswagger %}

{% swagger src="../../.gitbook/assets/states-api-spec.yaml" path="/states/{state}/admission" method="get" %}
[states-api-spec.yaml](../../.gitbook/assets/states-api-spec.yaml)
{% endswagger %}
