---
layout: default
---
# Contenta, Reservoir and the Bigger Drupal Community

Contenta provides you with examples of how to build your decoupled application
with a Drupal back-end. In fact it provides you with examples end to end, from
the JSON API server to the React
application (and [others](https://github.com/contentacms)).

Once you have explored the capabilities of decoupled Drupal, you can revert
Contenta to a clean state. That will give you a clean Drupal installation with
the modules necessary to start building **your** content model and **your** API.
When you do that there is no example content or configuration left. Everything
is reverted back to clean.

In summary, Contenta serves you both as inspiration, to build your project
following the best practices we provide in the demo project, and as a starting
point to build your project from scratch.

We summarize this in the following six stages.

![The Six Stages of Contenta](/assets/images/six-stages.jpg)

## Is collaboration possible?

A while after Contenta CMS started, Acquia released Reservoir. In [their blogpost](https://dev.acquia.com/blog/introducing-reservoir-a-distribution-for-decoupling-drupal/19/06/2017/18296)
they clarified that the project had been in the making for a long time. Longer
than Contenta.

> We are sad that Acquia released their own distribution to solve the same problem. But we are happy that the community has started to collaborate towards this goal. Future is still open. We continue believing in the full mission of contenta.

After several meetings between both API-First initiative
coordinators Wim (Reservoir) and Mateu (Contenta). The Contenta and Reservoir
teams came to an understanding of how the two projects compare. More importantly
a collaboration model was devised.

Suffice to say that the Contente team would have liked that there wasn't a split
that had to be merged afterwards. However it is highly important to note that
while the Reservoir team was working on it they provided many patches and
helpful discussions to the entire ecosystem (Drupal core, JSON API, Schemata ...). The reservouir team
involved in the weekly API-First meetings have been doing things the open source way, thank you!

## Which one should I use

After some debate and discussions the Contenta team and the Reservoir team
arrived to the conclusion that Contenta is a superset of Reservoir. Reservoir
does not attempt to have the examples of real life problems and how to solve
them in the front-ends and the back-end. Reservoir does not include the
_Knowledge Hub_ that Contenta includes. In fact Reservoir is only an alternative
to Contenta in (the critical) Stage 5.

It all comes down to what each consider baseline decoupled Drupal. Reservoir’s
approach is to give you a minimalistic set of features. For the Contenta team
this minimum includes more things. Things like a media library, helper modules
for front-end performance, tools to customize your API, etc.

In fact Reservoir only supports Nodes, Files and Users. Contenta supports all
the entity types Drupal offers (Comments, Media, Paragraphs, Redirects, …). The
Contenta's community feels that in real projects you will always need more than
those three entity types. The Reservoir team in Acquia feels that the vast
majority of the time you will not need anything else. This is **the fundamental
difference** between the projects as Stage 5.

![contenta-reservoir](/assets/images/contenta-reservoir.png)

## Contenta's Recommendation

> We [Contenta] are doing things this way because we believe it's the best
> approach. Understandably we believe that Contenta is the best solution for the
> vast majority of scenarios. However, we acknowledge that Reservoir can be a
> more suited solution for some.

Once you've gone through the stages 1 to 4, decide which project takes it from
here. If you are absolutely certain that you will not need taxonomy terms,
comments, media, etc. now or some time in the future, then Reservoir is the way
to go. In all the other scenarios we recommend Contenta.

Reservoir's focus is on simplicity. The Contenta team favors being ready with
the features that will solve your problems. We've had those problems in the
past.
