# Task

[![PyPI version](https://badge.fury.io/py/task-planner.svg)](https://badge.fury.io/py/task-planner)

## Overview

*Task* is a task planning tool for the command line.
By using a simple syntax, it allows you to keep track
of all you to-do's, e.g. add a task:
`python -m task add "<name>" priority <priority>`.

## Installation

```bash
python -m pip install task-planner
```

## Command reference

```
usage: python -m task [] [order] [add] [priority] [do] [done]

View all tasks:
python -m task
python -m task order <task|priority|status>

Add a task:
python -m task add "<name>"
python -m task add "<name>" priority <priority>

Set the priority of an existing task:
python -m task priority <priority> for <task id>

Set a task to doing:
python -m task do <task id>

Delete a task:
python -m task done <task id>
```

## License

Licensed under the [MIT License](https://github.com/yannickkirschen/task/blob/master/LICENSE).
Happy forking :)
