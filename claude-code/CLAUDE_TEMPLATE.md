# CLAUDE.md Template

This file provides templates for CLAUDE.md for each of development scenarios.

## development env
Mac OS Sequoia Version 15.5

## Make a notification with beep sound when Claude Code is waiting user input or the task is complete.

Use the command line below to notify the user every signle time Claude Code execution finishes, whether it's waiting for input or a task is complete.

```
osascript -e 'display notification "Waiting for your input" with title "Claude Code" sound name "Glass"'
```