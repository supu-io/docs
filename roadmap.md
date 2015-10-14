# supu.io : docs : roadmap

[< Return to index](README.md)

This is the roadmap document for the *supu.io* project. It describes the
remaining work to do.

It is a live document, it means that changes on this spec are and will be
comming if it is necessary. Nothing is fixed or closed unless we excplicity say
the contrary. So please put everything in doubt and keep the discussion
alive ;)

This document follows an idea started by Ubuntu, which consists in planning a
great but difficult bug 0 (our 1.0 version) to solve, so all minor versions &
milestones should refer this one and solve an small task and part of it.

## Versioning

For transparency into our release cycle and in striving to maintain backward
compatibility, all project components are maintained under
[the Semantic Versioning guidelines](http://semver.org/). Sometimes we screw
up, but we'll adhere to those rules whenever is possible.

We also follow the rule that one issue fixed should be a new minor release, so
expect to have a lot of minor version numbers changes, this will be normal.

### *0.1* : Managing issue tracker
- [x] [Issue Tracker interface](https://github.com/supu-io/issue-tracker/issues/1)
- [x] [Github Issue Tracker: Get a list of issues by status](https://github.com/supu-io/issue-tracker/issues/2)
- [x] [Github Issue Tracker: Update issue status](https://github.com/supu-io/issue-tracker/issues/3)
- [x] [Github Issue Tracker: Get issue details by id](https://github.com/supu-io/issue-tracker/issues/5)
- [x] [API to get a issues list by status](https://github.com/supu-io/api/issues/1)
- [x] [CLI to get a issues list by status](https://github.com/supu-io/cli/issues/1)
- [x] [API to get an issue details](https://github.com/supu-io/api/issues/2)
- [x] [CLI to get an issue details](https://github.com/supu-io/cli/issues/2)
- [x] [API to update an issue status](https://github.com/supu-io/api/issues/3)
- [x] [CLI to update an issue status](https://github.com/supu-io/cli/issues/3)
- [ ] Github Issue Tracker: Create new issue
- [ ] API: Create new issue
- [ ] CLI: Create new issue
- [x] Issue tracker setup
- [ ] [Github Issue Tracker: Add a comment to an issue](https://github.com/supu-io/issue-tracker/issues/4)
- [x] Vagrant box based on chef

### *0.2* : Linking the source control
- [ ] [Source Control interface](https://github.com/supu-io/source-control/issues/1)
- [ ] [Github Source Control: Add a comment to pull request](https://github.com/supu-io/source-control/issues/2)
- [ ] [Github Source Control: Create a pull request](https://github.com/supu-io/source-control/issues/3)
- [ ] [Github Source Control: Accept pull request](https://github.com/supu-io/source-control/issues/4)
- [ ] WebHooked API to support github payloads

### *0.3* : Accounts
- [ ] WEB: create an account
- [ ] WEB: Configure Github Issue tracker
- [ ] WEB: Configure Github Source Control

### *0.4* : Multiple issue trackers 
- [ ] Jira Issue Tracker: Get a list of issues by status
- [ ] Jira Issue Tracker: Update issue status
- [ ] Jira Issue Tracker: Add a comment to an issue
- [ ] Jira Issue Tracker: Get issue details by id
- [ ] WebHooked API to support Jira payloads
- [ ] Trello Issue Tracker: Get a list of issues by status
- [ ] Trello Issue Tracker: Update issue status
- [ ] Trello Issue Tracker: Add a comment to an issue
- [ ] Trello Issue Tracker: Get issue details by id
- [ ] WebHooked API to support Trello payloads
- [ ] WEB: configure your issue tracker

### *0.5* : Multiple source controls
- [ ] Bitbucket Source Control: Add a comment to pull request
- [ ] Bitbucket Source Control: Create a pull request
- [ ] Bitbucket Source Control: Accept pull request
- [ ] WEB: select your source control system
- [ ] WebHooked API to support Bitbucket payloads

### *Backlog*
- [ ] To be defined
- [ ] API Error control
