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

An **Ng Plain Class** in Angular 4 consists of an `export` statement ...

Coupled with the name of the `class` followed by ...

The Typescript style of variable declaration ie.) both name and type,

Followed by a `constructor` statement.

**Note**. ¡Recuerde! Typescript classes are EXPORTED and the act of exportation exposes the declared variables ( by type ) as well as the methods of the underlying Typescript class to the other components within your Angular 4 application at large.

## Ng Component Class

An **Ng Component Class** in Angular 4 also consists of an `export` statement ...

Coupled with the name of the `class` followed by

The Typescript style of variable declaration ie.) both name and type,

Followed by a `constructor` statement.

### Ng Component Top Aggregate Import Statement

But, in addition ...!

A Typescript class within an **Ng Component** may also show additional statements such as `implements` that points to an aggregate `import` statement at the top of the **Ng Component**, as follows:

#### Ng Component Class Statement

```liquid
{% raw %}
export class NameOfComponent implements OnInit {
{% endraw %}
```

#### Ng Component Import Component Statement

```liquid
{% raw %}
import { Component, OnInit } from '@angular/core';
{% endraw %}
```

### Ng Component Middle Ng Statement

Inside the **Ng Component Class** you may also find an `ng` statement similar to the `constructor` statement that also points to the `import` statement at the top of the **Ng Component**, as follows:

#### Ng Component Ng Statement

```liquid
{% raw %}
ngOnInit() {
    //
  }
{% endraw %}
```

#### Ng Component Import OnInit Statement

```liquid
{% raw %}
import { Component, OnInit } from '@angular/core';
{% endraw %}
```

**Note**. The `ng` statement is commonly placed below the `constructor` statement in the hierarchy of the **Ng Component Class**

### Ng Decorated Directives

Above the **Ng Component Class**, but below the **Ng Component Top Aggregate Import Statement** ... The Decorated Directive named 'Component' resides ie.) `@Component`.

```liquid
{% raw %}
@Component({
  selector: 'app-write-me',
  templateUrl: './write-me.component.html',
  styleUrls: ['./write-me.component.css']
})
{% endraw %}
```

**Note**. The Directive named 'Component' is decorated with three metadata sections as shown above ( selector, template, style ). In this case, the 'At' symbol, or `@` serves as the **Decorator Symbol**.

## Raw Code

More to come ...

```liquid
{% raw %}
`...`
{% endraw %}
```

***

**Sources**:

1. [ng-book 2: The Complete Guide to Angular by Nate Murray, Felipe Coury, Ari Lerner, and Carlos Taborda]. Published by © 2017 [Fullstack.io](https://www.ng-book.com/2){:target="_blank"}.

1. [Get Started With Angular by Martin Heller](https://){:target="_blank"}. Published by © 2017 [InfoWorld.com](https://www.infoworld.com){:target="_blank"}.