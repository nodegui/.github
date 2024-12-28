

# Contributing to NodeGui

:+1::tada: First off, thanks for taking the time to contribute! :tada::+1:

The following is a set of guidelines for contributing to NodeGui and its packages, which are hosted in the [NodeGui Organization](https://github.com/nodegui) on GitHub. These are mostly guidelines, not rules. Use your best judgment.


## Code of Conduct

This project and everyone participating in it is governed by the [NodeGui Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code. Please report unacceptable behavior to [admin@nodegui.org](mailto:admin@nodegui.org).


## What should I know before I get started?

### NodeGui and Packages

NodeGui is an open source project &mdash; it's made up of multiple repositories (https://github.com/nodegui).

NodeGui is designed on a plugin based architecture. This means that while it provides core features through the main package at https://github.com/nodegui/nodegui, many of its features and extensions will be implemented as plugins. For example, while the nodegui core package contains many useful widgets and APIs, newer and heavier features like webview will be implemented as a plugin.


#### Plugin Conventions

There are a few conventions around packages:
- All plugins should be named as nodegui-plugin-<name_of_plugin>. for example, if the plugin is webview, it would be called as nodegui-plugin-webview. This will allow users to search for plugins easily.

### Design Decisions

There are certain design decision made by the maintainers and the contributors of the project. Any major architectural changes will not be entertained at this time. This is because the project is at its infancy and the goal currently is to provide more features and usable widgets to the end users of this library. Although this will change in future if/when the project is adopted more or if need arises.

## How Can I Contribute?

### Reporting Bugs

This section guides you through submitting a bug report for NodeGui. Following these guidelines helps maintainers and the community understand your report :pencil:, reproduce the behavior :computer: :computer:, and find related reports :mag_right:.

While reporting a bug, please fill out [the required template](https://github.com/nodegui/.github/blob/master/.github/ISSUE_TEMPLATE/bug_report.md), the information it asks for helps us resolve issues faster. If the bug report is not filed with the issue template it might be closed without any response.

> **Note:** If you find a **Closed** issue that seems like it is the same thing that you're experiencing, open a new issue and include a link to the original issue in the body of your new one.

#### Before Submitting A Bug Report

* **Check the [FAQ](https://docs.nodegui.org/docs/faq).** You might be able to find the cause of the problem and fix things yourself. Most importantly, check if you can reproduce the problem [in the latest version of NodeGui]
* **Determine which repository the problem should be reported in**.
* **Perform a [cursory search](https://github.com/search?q=+is%3Aissue+user%3Anodegui)** to see if the problem has already been reported. If it has **and the issue is still open**, add a comment to the existing issue instead of opening a new one.


### Suggesting Enhancements

This section guides you through submitting an enhancement suggestion for NodeGui, including completely new features and minor improvements to existing functionality. Following these guidelines helps maintainers and the community understand your suggestion :pencil: and find related suggestions :mag_right:.

Before creating enhancement suggestions, please check the roadmap as you might find out that you don't need to create one. When you are creating an enhancement suggestion, please fill in [the template](https://github.com/nodegui/.github/blob/master/.github/ISSUE_TEMPLATE/feature_request.md), including the steps that you imagine you would take if the feature you're requesting existed.


#### Before Submitting An Enhancement Suggestion

*  Most importantly, check if you're using the latest version of NodeGui.
* **Check if there's already a third party plugin that provides this enhancement?**
* **Perform a [cursory search](https://github.com/search?q=+is%3Aissue+user%3ANodeGui)** to see if the enhancement has already been suggested. If it has, add a comment to the existing issue instead of opening a new one.
* If a enhancement can be created as a plugin, please try and implement it as a plugin instead of a core feature.

#### Enhancement that will not be considered at this time

* Any major architectural changes to the codebase: If the enhancement you want requires major architectural changes, there is a good chance that it will not be considered at this point of time.  This is because the project is at its infancy and the goal currently is to provide more features and usable widgets to the end users of this library. This will change in future if/when the project is adopted more or if need arises.

* Opinionated changes: Things like styleguide, linting, addition of external dependencies (including test framework) etc unless extrememly critical will not be considered at this time. Again, this will change in future once we reach a basic stable release. All these will be fixed by the core team and then we can have a discussion on what needs to be changed. Currently the project is in its experimental stage and hence nothing is really fixed.


#### Enhancements that will be considered

Anything that is not opinionated, helpful for the end user.
