---
layout: default
---
## [](#mission)Our Mission

Read more about Contenta's mission in [this blog post](medium.com/@mateu.aguilo.bosch/contenta-makes-your-content-happy-6f76bbe0cdae).

![The mission of Contenta CMS](/assets/images/contenta-mission.png)

## [](#quick-install)Quick install
<p style="text-align: center;">
  <iframe height="315" src="https://www.youtube.com/embed/MOQ0gd7uEWU" frameborder="0" allowfullscreen="" width="560"></iframe>
</p>

```bash
php -r "readfile('https://raw.githubusercontent.com/contentacms/contenta_jsonapi/8.x-1.x/installer.sh');" > contentacms.sh
chmod a+x contentacms.sh
./contentacms.sh
```

For this to work you will need to have composer installed in your local machine. See [get composer](https://getcomposer.org/) for more details. Also, make sure that the sqlite-extension is installed (`sudo apt-get install php-sqlite3` in debian/ubuntu).

The quick installation is intended for **local development** only.

## [](#goals)Goals
One of the conclusions of DrupalCon Baltimore was that Drupal 8 has **impressive tools to build a decoupled application**. However, assembling all the tools together and setting them up correctly can be a little bit daunting. On top of that, once you have everything set up you need to figure out the ins and outs of your front-end project.

With this in mind, Contenta CMS is born to _make your content happy_. Contenta CMS is the response of **the community** to build an API-First Drupal distribution. The goals of Contenta are simple: provide a standard platform that is API ready along with demo content and example front-end applications. In summary, Contenta intends to ease the pain of using, or simply trying, decoupled Drupal.

## [](#installation)Installation

* [Get composer](https://getcomposer.org/)
* Create a new project using a command like this. This will pull down the installation profile + core + modules, so maybe get a cup of tea:
```
composer create-project contentacms/contenta-jsonapi-project MYPROJECT --stability dev --no-interaction
```
* After that, install Drupal normally.

## [](#bigger-drupal-community)The Bigger Drupal Community

We know you have questions about the different API-First distributions. We had them as well recently. These are [some clarifications](/comparing-reservoir.html) that may help you.

## [](#demos)Demos
An integral part of Contenta is to provide an out of the box content model and demo content ready for you to start working with it. The demo chosen by the community is a [recipe magazine](https://www.drupal.org/node/2818741).

With this in mind, every demo consumer will implement this recipe magazine site with the goal in mind to compare the different implementations.

### [](#example-front-ends)Example Consumers

Choosing your own front-end technology is one of common reasons to choose a decoupled approach. In a decoupled architecture you can also have multiple front-ends at the same time. Contenta gives you examples on how to build a consumer application in different technologies.

We will implement the [same wireframes](https://www.drupal.org/node/2818741#comment-12122841) as the Out of the Box Initiative, so all the demo applications can be compared. Even though all applications will have the same structure, each one will choose their look and feel. Angular may use [material design](https://material.io/guidelines/material-design/introduction.html), elm may use [bootstrap](http://getbootstrap.com/), etc.

| Front-end | Status       | Example | Code   |
|:----------|:-------------|:--------|:-------|
| Angular   | Running demo | [Website](https://contenta-angular.firebaseapp.com/) | [Repo](https://github.com/contentacms/contenta_angular) |
| Elm       | Running demo | [Website](https://contenta-elm.firebaseapp.com/) | [Repo](https://github.com/contentacms/contenta_jsonapi__elm) |
| Ember     | Need help    | Not yet | [Repo](https://github.com/contentacms/contenta_ember) |
| Ionic     | Running demo | Not yet | [Repo](https://github.com/contentacms/contenta_ionic) |
| React     | In progress  | Not yet | [Repo](https://github.com/contentacms/contenta_react) |
| Vue.js    | Running demo | [Website](https://contentavuedemo.github.io/) | [Repo](https://github.com/contentacms/contenta_vue_nuxt) |

If you want to contribute to any of the demo apps above or add a new one, join [the Slack channel](https://drupal.slack.com/messages/C5A70F7D1) and become part of the project!

## [](#development)Development

Join the discussion in the [#contenta Slack channel](https://drupal.slack.com/messages/C5A70F7D1).

For documentation on the development on contenta_jsonapi itself, see [docs/development](https://github.com/contentacms/contenta_jsonapi/blob/8.x-1.x/docs/development.md).

