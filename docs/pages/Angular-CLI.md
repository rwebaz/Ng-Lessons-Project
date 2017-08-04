---
title: Angular CLI
layout: default
navigation_weight: 9
---
# Angular CLI

The **Angular CLI** is the Terminal engine of Angular 4.

## Ng How To Upgrade Angular CLI From The Terminal

When installing globally, use the `-g` switch.

When installing locally, use the 



## Table O Contents

- TOC
{:toc}

## Set the Session Ruby

From the base Terminal prompt ( your-machine-name:~ your-root-directory$ ) ...

```liquid
{% raw %}
rvm use 2.4.1
{% endraw %}
```

## Uninstall Angular CLI

First, uninstall any old versions of the Angular CLI.

From the base Terminal prompt ( your-machine-name:~ your-root-directory$ ) ...

```liquid
{% raw %}
npm uninstall -g @angular/cli
{% endraw %}
```

**Note**. As of npm ver 5.0, the npm cache self-heals from corruption issues and data extracted from the cache is guaranteed ( by npm ) to be valid. Therefore, there is no need to use `npm cache clean` after performing the `uninstall` step above.

## Re-Install Latest Version

Second, reinstall the latest version of the Angular CLI.

From the base Terminal prompt ( your-machine-name:~ your-root-directory$ ) ...

```liquid
{% raw %}
npm install -g @angular-cli@latest
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

## Ng How To Install Angular CLI Locally

From the **Finder** in Mac Os Sierra ...

1. Right-click over the project folder of your Angular 4 Application
1. CLICK **Services**
1. SELECT new folder at Terminal.

## Set the Session Ruby

From the project Terminal prompt ... ( your-machine-name:ng-project-name your-root-directory$ )

```liquid
{% raw %}
rvm use 2.4.1
{% endraw %}
```

## Install the **Latest Version** of **Angular CLI** to your project

From the project Terminal prompt ... ( your-machine-name:ng-project-name your-root-directory$ )

```liquid
{% raw %}
npm install --save-dev @angular-cli@latest
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

**Source**: [Angular CLI Home Page by ... Published by © 2017 Google.io](https://cli.angular.io){:target="_blank"}
