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

## Important URLs

List of triggers:

https://docs.github.com/en/actions/reference/events-that-trigger-workflows

Github Action Market Place:

https://github.com/marketplace?category=publishing&type=actions&query=AWS+

Creating GH actions:

https://docs.github.com/en/actions/creating-actions/publishing-actions-in-github-marketplace

Self hosted runners:

https://docs.github.com/en/actions/hosting-your-own-runners


Auto Completion:

https://github.blog/2019-10-01-new-workflow-editor-for-github-actions/
