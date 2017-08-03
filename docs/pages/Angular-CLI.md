---
title: Angular CLI
layout: default
navigation_weight: 9
---
# Angular CLI

The **Angular CLI** is the Terminal engine of Angular 4.

## Ng How To Upgrade Angular CLI From The Terminal

More to come ...

**Note**. As of npm ver 5.0, the npm cache self-heals from corruption issues and data extracted from the cache is guaranteed to be valid. Therefore, there is no need to use `npm cache clean` after performing the `uninstall` step below.

## Table O Contents

- TOC
{:toc}

## Initialize Session Ruby

From the base Terminal prompt ( your-machine-name:~ your-root-directory$ ) ...

```liquid
{% raw %}
rvm use 2.4.1
{% endraw %}
```

## Uninstall Angular CLI

From the base Terminal prompt ( your-machine-name:~ your-root-directory$ ) ...

```liquid
{% raw %}
npm uninstall -g @angular/cli
{% endraw %}
```

## Re-Install Latest Version

From the base Terminal prompt ( your-machine-name:~ your-root-directory$ ) ...

```liquid
{% raw %}
npm install -g @angular/cli@latest
{% endraw %}
```

## Check Version

From the base Terminal prompt ( your-machine-name:~ your-root-directory$ ) ...

```liquid
{% raw %}
ng --version
{% endraw %}
```

Returns ...

```liquid
{% raw %}
    _                      _                 ____ _     ___
   / \   _ __   __ _ _   _| | __ _ _ __     / ___| |   |_ _|
  / △ \ | '_ \ / _` | | | | |/ _` | '__|   | |   | |    | |
 / ___ \| | | | (_| | |_| | | (_| | |      | |___| |___ | |
/_/   \_\_| |_|\__, |\__,_|_|\__,_|_|       \____|_____|___|
               |___/
@angular/cli: 1.2.6
node: 7.7.4
os: your machine operating system
{% endraw %}
```

## Check Where Version Is Located Locally

From the base Terminal prompt ( your-machine-name:~ your-root-directory$ ) ...

```liquid
{% raw %}
which ng
{% endraw %}
```

Returns ...

```liquid
{% raw %}
/usr/local/bin/ng
{% endraw %}
```

## Raw Code

More to come ...

```liquid
{% raw %}
`...`
{% endraw %}
```

***

**Source**: [ng-book 2: The Complete Guide to Angular by Nate Murray, Felipe Coury, Ari Lerner, and Carlos Taborda. Published by © 2017 Fullstack.io](https://www.ng-book.com/2){:target="_blank"}
