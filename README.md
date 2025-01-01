# Ai-News
An Orchestration of Ai Agents Created using Crew Ai. . This is a Ai news that searches for the latest news on the given topic and gives a summary of the news
Agents used : News Researcher
News Scrapper and Reporter

Tools used to power the agent : Serper


## Installation

Ensure you have Python >=3.10 <=3.13 installed on your system. This project uses [UV](https://docs.astral.sh/uv/) for dependency management and package handling, offering a seamless setup and execution experience.

First, if you haven't already, install crew ai:

```bash
pip install crewai
```
install tools library

```bash
pip install crewai-tools
```

Next, navigate to your project directory and install the dependencies:

(Optional) Lock the dependencies and install them by using the CLI command:
```bash
crewai install
```
### Customizing

**Add your `OPENAI_API_KEY` into the `.env` file**
**Add `SERP_API_KEY` into `.env` fiele

## Running the Project

To kickstart your crew of AI agents and begin task execution, run this from the root folder of your project:

```bash
$ crewai run
```

This command initializes the ai-news Crew, assembling the agents and assigning them tasks as defined in your configuration.

## Understanding Your Crew

The ai-news Crew is composed of multiple AI agents, each with unique roles, goals, and tools. These agents collaborate on a series of tasks, defined in `config/tasks.yaml`, leveraging their collective skills to achieve complex objectives. The `config/agents.yaml` file outlines the capabilities and configurations of each agent in your crew.


