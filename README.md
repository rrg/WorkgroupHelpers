# WorkgroupHelpers
Sublime Text plugin to help manage workgroups
This plugin helps manage open workgroups and panes on sublime text.

It currently supports two commands:

# Cycle Workgroups:
Toggle between currently open workgroups (use direction -1 to go left)
	{ "keys": ["alt+tab"], "command": "cycle_workgroup", "args": { "direction": 1} },

Move a file to next and previous workgroups (use direction -1 to go left)
  { "keys": ["alt+right"], "command": "move_to_workgroup", "args": { "direction": 1} },


