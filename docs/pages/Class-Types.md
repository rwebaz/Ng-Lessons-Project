---
title: Class Types
layout: default
navigation_weight: 9
---
# Class Types

The difference between an **Ng Plain Class** and an **Ng Component Class** is simply one of complexity.

## Table O Contents

- TOC
{:toc}

## Ng Plain Class

An **Ng Plain Class** in Angular 4 consists of an `export` statement coupled with the name of the `class` followed by the Typescript style of variable declaration ie.) both name and type, followed by a `constructor ` statement.

## Ng Component Class

An **Ng Component Class** in Angular 4 also consists of an `export` statement coupled with the name of the `class` followed by the Typescript style of variable declaration ie.) both name and type, followed by a `constructor ` statement.

However, a class within an **Ng Component** may also show additional statements such as `implements` that points to an `import` statement at the top of the **Ng Component**, as follows:

### Ng Component Top Import Statement

```liquid
{% raw %}
import { Component, OnInit } from '@angular/core';
{% endraw %}
```

### Ng Component Class Statement

```liquid
{% raw %}
export class WriteMeComponent implements OnInit {
{% endraw %}
```

Inside the **Ng Component Class** you may also find an `ng` statement similar to the `constructor` statement that also points to the `import` statement at the top of the **Ng Component**, as follows:

ngOnInit() {
    //
  }

**Note**. The `ng` statement is commonly placed below the `constructor` statement in the hierarchy of the **Ng Component Class**

### Ng Component Decorator

Above the **Ng Component Class**, but below the **Ng Component Top Import Statement** ... The `@Component` decorator resides, as follows:

```liquid
{% raw %}
@Component({
  selector: 'app-write-me',
  templateUrl: './write-me.component.html',
  styleUrls: ['./write-me.component.css']
})
{% endraw %}
```

**Note**. The three sections of the **Ng Component Decorator** shown above ( selector, template, style ) require explicit declaration and location.

## Raw Code

More to come ...

```liquid
{% raw %}
`...`
{% endraw %}
```

***

**Source**: [ng-book 2: The Complete Guide to Angular by Nate Murray, Felipe Coury, Ari Lerner, and Carlos Taborda. Published by © 2017 Fullstack.io](http://cowles.yale.edu/sites/default/files/files/pub/d20/d2069.pdf){:target="_blank"}