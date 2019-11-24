---
title: App Shell
layout: default
excerpt: Angular applications tend to load late. To correct this anomaly, we must pre-render a part of your index page ...
hint: Place the intro paragraph ie.) the 'hypothesis' here ...
repo: Ng-Lessons-Project
ver_date: 11-20-19
navigation_weight: 8
categories: page
---
{% include toc.md %}

## Angular CLI

> **Hint**. {{ page.hint }}

To *pre-render* a part of the content of your new Angular app [[2](#AU){:.red}] ...

- From the local Terminal prompt `$` of your `app` directory

- Type the following command statement

```liquid
{% raw %}
ng generate universal ngu-app-shell
{% endraw %}
```

## Last Subtitle

More to come ...

### Test Errata

The following snippet of code renders a raw liquid tag ...

```liquid
{% raw %}
test errata
{% endraw %}
```

***

**Note**. The above synopsis was derived from an article written by Vasco [[1](#VASCO){:.red}].

1. {:#VASCO}[Angular App Shell by Vasco](https://www.angular-university.io){:title="Click to Visit Angular University Online"}{:target="_blank"}

1. {:#AU}[Angular-university.io](https://www.angular-university.io){:title="Click to Visit the Angular University Online"}{:target="_blank"}.

***

{% include patreon-link.md %}
