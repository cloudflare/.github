# Contributing

Welcome to Cloudflare OpenSource! We're super excited to have you here. This document contains
the best practices for contributing to our repositories.

## Filing an Issue

If you are using one of our open source projects- you'll likely begin interacting with us by
filing an issue. Regardless of whether you think the issue is with the project itself, if you're
having trouble using the project, feel free to file an issue on the repo.

**If you have a feature request, please file an issue before making a PR.** Everyone's time is
incredibley valuable, so if you have an idea for a feature, please file an issue. This way we
can have a discussion with you, and the community, about the design, before you have sunk a
bunch of time into developing it. 

**You do not need to file an issue for small fixes.** If you are fixing a typo or refactoring
a bit of code, you likely don't need to file an issue. This is a judgement call, and *sometimes*
we may review your PR and ask you to file an issue if we expect there are larger design decisions
to be made.

**Each repository has an Issue Template.** This helps us make sure that you can give us the most
information about your issue upfront, so we can limit the amount of back and forth required
before your issue can be resolved. Do your best to fill it out, but if you have trouble, it's
ok to file an incomplete issue template.

## Making a PR

**If you are considering filing a pull request, make sure that there's an issue filed for the work
you'd like to do.** There might be some discussion required! Filing an issue first will help ensure
that the work you put into your pull request will get merged.

Once your PR is made, it will be labelled *needs review*. A maintainer will review your PR as soon
as they can. The reviewer may ask for changes- they will mark the PR as *changes requested* and
*work in progress* and will give you details about the requested changes. Feel free to ask lots of
questions! The maintainers are there to help you!

### IDE Configuration Files

Machine specific configuration files may be generaged by your IDE while working on the project. Please make sure to add these files to a global .gitignore so they are kept from accidentally being commited to the project and causing issues for other contributors.

Some examples of these files are the .idea folder created by JetBrains products (WebStorm, IntelliJ, etc) as well as .vscode created by Visual Studio Code for workspace specific settings.

For help setting up a global `.gitignore` check out this [GitHub article](https://help.github.com/articles/ignoring-files/#create-a-global-gitignorea)!

## Conduct

Cloudflare OpenSource follows the [Contributor Covenant Code of Conduct]. You can find a copy in each
of our repositories. Violating the CoC could result in a warning or a ban to any and all repositories
in this origanization.

[Contributor Covenant Code of Conduct]: CODE_OF_CONDUCT.md

## Contact

If you have any questions, please reach out to [opensource@cloudflare.com](mailto:opensource@cloudflare.com).

