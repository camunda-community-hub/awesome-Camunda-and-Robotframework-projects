# Awesome Camunda and Robotframework projects
[Robotframework](https://robotframework.org/) is an Open Source framework that can be used for test automation and for robotic process automation (RPA). There are various ways how Robotframework can be combined with Camunda. This repo is a collection of projects around Robotframework in combination with Camunda. 

## External Task clients
Robotframework is Python based. Therefore, it uses Camunda's REST Api. There are various External Task Clients written in Python that can be used. 

There is one External task client that is specific for Robotframework. It enables the usage of keywords in Robotframework tasks to communicate with Camunda: 
 - [Robotframework External Task client](https://github.com/MarketSquare/robotframework-camunda)
 - [Project](https://gitlab.com/noordsestern/camunda-invade-example) (a showcase, how to use the External Task Client above)
 - [Blogpost](https://www.postadress-techblog.de/post/camunda-robot-framework) (for more information on the External Task Client)
 - [Talk](https://robocon.io/#robotframework-camunda-library:-orchestrating-robotic-tasks-with-camunda)


## Robotframework task orchestration with Camunda
If you use Robotframework already Camunda can help you with orchestrating your Robotframework tasks. A Robotframework task is like a Service task.  Here is an example project

 - [Project](https://github.com/TheProjectAurora/camunda-robotframework-demo/)
 
 
## Robotframework for UI Automation
If you use Camunda already Robotframework can help you with UI Automation. It provides an Open Source RPA solution. Here is an example how this can be implemented:
- [Project](https://gitlab.com/atsoukka/robot-rpa-playground/)
 
## Running Robotframework bots
In order to run the Robotframework bots there are various options.

### Nomad
- [Project](https://gitlab.com/vasara-bpm/camunda-nomad-client/)
- [Blogpost](https://datakurre.pandala.org/2021/04/camunda-nomad-robotframework-rpa/)


