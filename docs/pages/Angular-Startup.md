---
title: Angular Startup
layout: default
navigation_weight: 9
---
# Angular Startup

Place the introducing line of text ie.) the 'tagline' here ...

Or, place the site dot tagline here.

{{ site.tagline }}

{% include toc-flammarion.md %}

## Open Global Terminal Window

From the Dock in Mac OS High Sierra, click on your Terminal program.

## Set Global Ruby Version

First, from the open global Terminal window, set the current version of ruby, as follows:

```liquid
{% raw %}
rvm use 2.4.1
{% endraw %}
```

## Set Global Node Version

Secondly, from the open global Terminal window, set the current version of node, as follows:

```liquid
{% raw %}
nvm use 8.9.1
{% endraw %}
```

## Install Angular CLI Globally

Finally, from the open global Terminal window, type the following command to install Angular globally using the *Node Package Manager*, or **NPM**.

```liquid
{% raw %}
npm install -g @angular/cli
{% endraw %}
```

## Create New Angular App

To create a new angular application, select a directory ( desktop ), and right click to summon a local Terminal window.

### Open Local Terminal Window

From the Finder in Mac OS High Sierra, right click over the folder of your selected directory ( desktop ).

Select Services, and click on "New Folder at Terminal".

From the local Terminal prompt, type the following command:

```liquid
{% raw %}
ng new testapp
{% endraw %}
```

The Angular CLI will now scaffold a new app named 'testapp'.

### Serve the New App

To serve your app through your local browser at the default localhost port 4200, type the following command at your local Terminal prompt, as follows:

```liquid
{% raw %}
ng serve -o
{% endraw %}
```

## Subtitle

Place the introducing line of text ie.) the 'tagline' here ...

```liquid
{% raw %}
test errata
{% endraw %}
```

{% include sources-and-uses.md %}

### External Sources

- The [Project Source Links](https://mminail.github.io/NG/Source-NG-Links.htm){:title="Click to Visit the Source Links page of the NG Lessons Project at GitHub pages"}{:target="_blank"} page of the NG Lessons Project. Published by © 2017 [Mminail.github.io](https://mminail.github.io/){:title="Click to Visit the Concept Library of the Medical Marijuana Initiative of North America - International Limited, an Arizona Benefit Corporation"}{:target="_blank"}.
