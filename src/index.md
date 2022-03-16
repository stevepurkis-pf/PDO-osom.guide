---
layout: document
subtitle: PDO Services Model
tags:
- homepage

---
## The PDO Services Model

### The PDO Executive

The [PDO Executive](/executive) governs the network of services and holds the managers  of those services to account through various mechanisms documented in terms of reference.

The executive also has a role in advocating and monitoring the adoption of [guides to better decisions](/doctrine) throughout the organisation, which is a collection of 40 universally useful patterns of behaviour.

### The service network

[Services](/services/) exist to address their [users' needs](/user-needs) (users may be external to the organisation, internal, or a mixture of both). These needs are documented in a [service contract](/service-contract) to help manage expectations.

Each service is built & operated by a [Service Manager](/service-managers), who is accountable for running the service in all its [lifecycle phases](/lifecycle) - from discovery until its eventual retirement.  They are given full autonomy, and are held to account in regular [assessments](/assessments) by the PDO Executive.

#### Context

The PDO Services model is based on [Organised Services Operating Model (OSOM)](https://osom.guide), which evolved by encouraging the [guides to better decisions](/doctrine) at multiple organisations.

#### Recent changes

{% for article in collections.all limit:5 reversed %}
{% if article.data.subtitle.length > 0 %}

1. [{{ article.data.subtitle }}]({{ article.url }})
   {% endif %}
   {% endfor %}