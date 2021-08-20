[![Github Action CI Demo](https://github.com/asksmruti/demo/actions/workflows/ci-demo.yml/badge.svg)](https://github.com/asksmruti/demo/actions/workflows/ci-demo.yml)
[![Github Action Rollback Demo](https://github.com/asksmruti/demo/actions/workflows/rollback.yml/badge.svg)](https://github.com/asksmruti/demo/actions/workflows/rollback.yml)
[![Github Action Security scan Demo](https://github.com/asksmruti/demo/actions/workflows/security-scan-demo.yml/badge.svg)](https://github.com/asksmruti/demo/actions/workflows/security-scan-demo.yml)

[![codecov](https://codecov.io/gh/asksmruti/demo/branch/main/graph/badge.svg?token=NP7RSB1OQC)](https://codecov.io/gh/asksmruti/demo)


[comment]: <> ([![Codecov]&#40;https://codecov.io/gh/asksmruti/demo/branch/main/graph/badge.svg?token=xxxxxx&#41;]&#40;https://codecov.io/gh/asksmruti/demo&#41;)

[comment]: <> (![Open Issues]&#40;https://img.shields.io/github/issues/asksmruti/demo&#41;)

[comment]: <> (![Open PRs]&#40;https://img.shields.io/github/issues-pr-raw/asksmruti/demo&#41;)

# Github action demo


About
------
This repository consists of -
* Sample github actions workflows
* Flask API code for a sample dashboard

It is for demo purpose of github action.

Table of contents
------------------

- [What is github action?](#what-is-github-action)
- [Development workflows](#development-workflow)
- [Github event and action](#github-events-actions)
- [Demo](#demo)

## What is github action?
Github action is a platform to automate the software development workflows.from within GitHub. 
You can deploy workflows in the same place where you store code and collaborate on pull requests and issues.


## Development workflows
A development workflow is series of actions. CI/CD is not the only workflow.
All the organizational task can be a series of actions and can be automated through different work flows. 
eg. adding contributors, pull request manage, adding comments to issues/PRs, release management etc.


## Github event and action
_Event_: When something happened in or to your repository,(eg. raising a PR.) the github API generates an event.

_Action_: Listen the event and trigger a job automatically is called action.
Series of action is called actions which makes the workflow.

## Demo
Please go through the workflows located `.github/workflows/`

Note - The workflow files location is always `.github/workflows/`