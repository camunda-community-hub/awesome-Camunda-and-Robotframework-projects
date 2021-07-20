# Awesome Camunda and Robot Framework Projects

[Robot Framework](https://robotframework.org/) is an open source framework that can be used for many kinds of automation from test automation to [Robotic Process Automation (RPA)](https://robotframework.org/rpa/). Robot Framework has [a huge ecosystem](https://pypi.org/search/?q=robotframework), and being written in Python, it can be natively integrated with Python ML ecosystem.

There are various ways that Robot Framework can be combined with Camunda. This repository is a collection of projects centered around using Robot Framework in combination with [Camunda](https://camunda.com/).


## External Task Clients

Robot Framework is Python based. Therefore, it uses [Camunda's REST API](https://docs.camunda.org/manual/7.15/reference/rest/) to integrate with Camunda. There are various External task clients written in Python that can also be used.

There is one External task client that is implemented as Robot Framework keyword library. It enables the use of keywords in Robot Framework tasks to communicate with Camunda:

- [Robot Framework Camunda Library](https://github.com/MarketSquare/robotframework-camunda)
- [Roman Empire Invades Robot Framework Project](https://gitlab.com/noordsestern/camunda-invade-example) (This is an example scenario using the Roman Empire of how to use the External task client listed above with Robot Framework)
- [Automate This! 'Camunda and Robot Framework' Blogpost](https://www.postadress-techblog.de/post/camunda-robot-framework) (for more information on the External task client)
- [Robocon 2021 Presentation: 'Orchestrating Robotic Tasks with Camunda'](https://robocon.io/#robotframework-camunda-library:-orchestrating-robotic-tasks-with-camunda) presented by [Markus Stahl](https://gitlab.com/noordsestern)

There is another incubating External task client, which uses Robocorp [RCC toolchain](https://robocorp.com/docs/rcc/overview) for executing Robot Framework bots:

* [carrot-rcc](https://pypi.org/project/carrot-rcc/) – Camunda external task Robot Framework RCC client


## Robot Framework task orchestration with Camunda

If you're using Robot Framework already, Camunda can help you with orchestrating your Robot Framework tasks. A Robot Framework task is like a Service task. Here is an example project with a custom External taskkclient, which spawns Docker containers running Robot Framework to complete External tasks:

- [NorthCode's 'The Project Aurora' Camunda Robot Framework Demo](https://github.com/TheProjectAurora/camunda-robotframework-demo/)


## Robot Framework for UI automation

If you're already using Camunda, Robot Framework can help you with User Interface (UI) automation by providing an open source RPA solution. Here is an example of how this can be implemented for browser automation:

- [Robot Framework Camunda RPA Playground](https://gitlab.com/atsoukka/robot-rpa-playground/) by [Asko Soukka](https://datakurre.pandala.org/)


## Running Robot Framework Bots

There are various options one can use to run Robot Framework bots. To get started, we suggest reading the [Robot Framework User Guide](https://robotframework.org/robotframework/latest/RobotFrameworkUserGuide.html)


## Working with Nomad

[The Nomad Project](https://www.nomadproject.io/docs/internals/scheduling/scheduling) is a scheduling tool developed by Hashicorp that one can use when working with Camunda and Robot Framework. There is a project, which aims to schedule Service tasks as parameterized Nomad jobs:

- [Camunda Nomad Client](https://gitlab.com/vasara-bpm/camunda-nomad-client/)
- ['My Dream Open Source RPA orchestrator with Camunda and Nomad'](https://datakurre.pandala.org/2021/04/camunda-nomad-robotframework-rpa/) by [Asko Soukka](https://datakurre.pandala.org/)
