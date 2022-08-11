# Slack's Next Generation Platform on Gitpod

This repo is the fastest way to get up running on Slack's Next Generation Platform using Gitpod. Within seconds, have an environment for developing on Slack running VS Code in your browser.

## Prerequisites

- [Gitpod account](https://gitpod.io/) (their [free plan](https://www.gitpod.io/pricing) is very generous!)
- Access to [Slack's Next Generation](http://api.slack.com/future) - DM [@hirefrank](https://twitter.com/hirefrank) for access.

## Get started

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/hirefrank/slack-platform-gitpod)


## How this works
See `.gitpod.yml` for details.

- Provisions a development environment with the latest version of Deno and the Slack CLI
- Bootstraps your project with the [starter template](https://github.com/slack-samples/deno-starter-template).
- Removes _git remote.origin.url_ so you can set your own
