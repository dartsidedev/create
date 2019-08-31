# `create`

**This project is still in its very early stages. I'm still just figuring out the interface for the project and researching other scaffolding tools in both Dart land and other programming languages.**

**With this project, I'm following "interace-driven development": I write down how the tool I wish existed would behave and I document how I would trigger these commands. Most of the commands in this `README` do not work at the moment, they are just my vision for this project.**

## Let's `create` amazing Dart apps!

Dart has a huge, unlocked potential for becoming *the* full-stack language for the coming years. You run the code you write in Dart on the server, in the browser and on both of the largest mobile platforms, iOS and Android. I believe that the community solutions, the ecosystem will catch up, which in turn encourage more effort spent on making the language better and the runtime faster.

`create`'s vision is to make sharing templates within the community easy.

* You want a Flutter app that follows your favorite state management patterns?
* Your team is just getting started with Dart and you don't want to figure out all the linting, testing, formatting and tooling issues, you just want these to be there and you want to run all the automated checks in your continuous integration pipeline, so that your team abides by the rules?
* You want a full-blown, full-stack project that creates a mobile app, Dart backend, and web admin interface? This package should enable the community to make these things happen.
* You feel like you want to create tens of Flutter plugins, but you are being slowed down and limited by the default template? You want your plugins neat, you establish some practices and coding patterns and you want these plugins to be consistent.


## Current stage

I'm still researching options. In the Dart community, we have `stagehand` and `flutter create` which strangely enough, are two different templating solutions (I mean, could you just agree on one?).

If you are new to Dart and Flutter, maybe you should try `stagehand` or `flutter create` first. They are opinionated and they are maintained by the Dart and Flutter teams.

## Goals

* **Unopinionated and free.** Though Dart is not a new language, I believe we are seeing the renaissance of the language, and thus, we should be able to express and share all ideas and let the best approaches win.
* **Support for all-things Dart.** I want this package to enable the community to create templates for whatever they want. Mobile apps, command-line apps, AWS Lambdas, backend, frontend, full-stack. Plugins, packages, demo apps. Anything you want to share.
* **Engine distributed as a pub package. Templates distributed as pub packages.** For Dart developers, the pub is the central point for packages. I want to provide alternatives for templates, such as git repos and local folders.

## Issues that this package should solve

https://github.com/flutter/flutter/issues/13611
https://github.com/flutter/flutter/issues/18819
https://github.com/flutter/flutter/issues/15279
https://github.com/flutter/flutter/issues/14719
