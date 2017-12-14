---
title: Angular Start
layout: default
navigation_weight: 2
---
# Angular Start

How to establish the Angular CLI in Mac Os High Sierra ...

{% include toc-flammarion.md %}

## Terminal Preparation

Before we can operate on an Angular program it will be wise to ensure a couple of system variables are set properly.

### Global Ruby Version

First, from an open global Terminal window pointing to your developer home directory ...

- Set the current version of **ruby**, as follows:

```liquid
{% raw %}
rvm use 2.4.1
{% endraw %}
```

**Note**. If you have not yet established a *Ruby Version Manager*, please do so now at [rvm](https://www.rvm.com){:title="Click to Visit the Ruby Version Manager"}{:target="_blank"} [[3](#NVM){:.red}].

### Global Node Version

Secondly, from an open global Terminal window pointing to your developer home directory ...

- Set the current version of **node**, as follows:

```liquid
{% raw %}
nvm use 8.9.2
{% endraw %}
```

**Note**. If you have not yet established a *Node Version Manager*, please do so now at [nvm](https://www.nvm.com){:title="Click to Visit the Node Version Manager"}{:target="_blank"} [[2](#RVM){:.red}].

### Global Angular Version

Thirdly, from an open global Terminal window pointing to your developer home directory ...

- Uninstall any old version of the Angular CLI that may still be globally resident on your machine, as follows:

```liquid
{% raw %}
npm uninstall -g @angular/cli
{% endraw %}
```

- Restart the Terminal

Next, install the current stable version of the *Angular CLI* using the *Node Package Manager*, as follows:

```liquid
{% raw %}
npm i -g @angular/cli
{% endraw %}
```

**Note**. As of npm ver 5.0, the npm cache self-heals from corruption issues and data extracted from the cache is guaranteed by npm to be valid. Therefore, there is no need to use `npm cache clean` after performing the `uninstall` step above.

To check the now current version of Angular CLI installed on your development machine ...

- Type the following command statement at the local Terminal prompt `$`

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

Angular CLI: 1.6.0
Node: 8.9.2
OS: darwin x64
Angular: 
...
{% endraw %}
```

To check the physical disk location of the current version of your **Angular CLI** ...

- From the local Terminal prompt `$` of your development machine

- Type the following command statement

```liquid
{% raw %}
which ng
{% endraw %}
```

Returns ...

```liquid
{% raw %}
/Users/yourHomeDirectory/.nvm/versions/node/v8.9.2/bin/ng
{% endraw %}
```

## App Creation

To create a new Angular 5 application with routing enabled ...

### Visual Studio Code

To create a new Angular 5 app from the command line ...

- From the local Terminal prompt `$` inside the *View*, *Integrated Terminal* feature of **Visual Studio Code**

- Type the `ng new` command statement with the *routing* switch `--` enabled, as follows:

```liquid
{% raw %}
ng new shell-one --routing
{% endraw %}
```

**Note**. In this case, we have given the new application a name of `shell-one`.

If you wish to give your new app **S-Css** capability "right out of the box" ...

- Enable the *scss* switch `--` in the above `ng new` command statement, as well

- Right after the *routing* switch `--`, as follows:

```liquid
{% raw %}
ng new shell-one --routing --scss
{% endraw %}
```

### Terminal Window

Alternatively, you may also initiate the above command statement directly from a local Terminal window, as follows:

- From the *Finder* in **Mac Os High Sierra**, right click over the `src` subdirectory of your **My_NG** directory

- Select *Services*, *New Terminal at Folder*

- Type the `ng new` command statement with the *routing* switch `--` enabled, as shown above.

**Note**. **Flags** have a single hyphen prefix `-` whereas **Switches** have a double-hyphen prefix `--`.

### Service Open

To serve your new app through a window of your local default browser, and to listen for changes ...

- From either your local Terminal window prompt `$`, or

- From within the *View*, *Integrated Terminal* feature of **Visual Studio Code** ...

- Type the `ng serve` command statement with the *open* flag enabled `-o`, as follows:

```liquid
{% raw %}
ng serve -o
{% endraw %}
```

**Note**. The default port for service and listening to Angular apps on your development machine is port 4200.

Whereas, the default port for service and listening to Jekyll apps on your development machine is port 4000.

## Last Subtitle

Place the introducing line of text ie.) the 'tagline' here ...

```liquid
{% raw %}
test errata
{% endraw %}
```

{% include sources-and-uses.md %}

1. {:#NVM}The [Node Version Manager](https://nvm.com){:title="Click to Visit the Node Version Manager"}{:target="_blank"}. Published by © 2017 [Nvm.io](https://nvm.io/){:title="Click to Visit the Node Version Manager"}{:target="_blank"}.

1. {:#RVM}The [Ruby Version Manager](https://rvm.com){:title="Click to Visit the Ruby Version Manager"}{:target="_blank"}. Published by © 2017 [Rvm.io](https://rvm.io/){:title="Click to Visit the Ruby Version Manager"}{:target="_blank"}.

### External Sources

- The [Project Source Links](https://mminail.github.io/Ng/Source-Ng-Links.htm){:title="Click to Visit the Source Links page of the Ng Lessons Project at GitHub pages"}{:target="_blank"} page of the Ng Lessons Project. Published by © 2017 [Mminail.github.io](https://mminail.github.io/){:title="Click to Visit the Concept Library of the Medical Marijuana Initiative of North America - International Limited, an Arizona Benefit Corporation"}{:target="_blank"}.

- {:#MARTINHELLER}[Get Started w Angular by Martin Heller](https://nvm.com){:title="Click to Visit the Get Started With Angular by Martin Heller"}{:target="_blank"}. Published by © 2017 [InfoWorld.com](https://cli.angular.io){:target="_blank"}.

- {:#KIMMAIDA}[Real-world Angular Series - Part One: MEAN Setup & Angular Architecture by Kim Maida](https://auth0.com/blog/real-world-angular-series-part-1/){:title="Click to Visit the Real-world Angular Series - Part One"}{:target="_blank"}. Published by © 2017 [Auth0.com](https://auth0.com/){:title="Click to Visit Auth Zero dot com"}{:target="_blank"}.
