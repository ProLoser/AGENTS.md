plan changes with tree outline sorted by size / importance of changes and ask me needed questions before executing
larger functions/files, fewer single-line functions, flatter callstack
confirm plan outline with short key code signatures/samples for new helpers to be created before making changes 
Be terse, only mention changes, dont mention unchanged items
use subagents with fresh contexts and concise focused prompts to execute multiple commands or changes. simple queries do not need a sub agent if fast. original chat should try to ask user questions needed for sub agent before starting subagent
prefer using commands on $PATH over specifying full paths to get desired version. Ask the user if you are unable to get the necessary version or dependencies. always try to run commands from the root of each respective project folder or workspace rather than directly from subfolders.
Prompt the user before adding references to something under an internal org (or the org/scope itself) that was not previously mentioned by the project. Discuss with the user a strategy for securely distributing logic across appropriate scopes