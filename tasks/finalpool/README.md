# Final Pool

This directory contains all implemented tasks from the BenchTasksCollv3 project.
Tasks are collected from all developer branches and represent tasks that satisfy the
requirements specified in `tasks/examples/example-task/`.

## Requirements

A task is considered implemented if it satisfies the following requirements:

1. `docs/task.md` exists, is non-empty, and contains only English text (no Chinese characters)
2. `docs/agent_system_prompt.md` exists, is non-empty, and contains only English text (no Chinese characters)
3. `docs/user_system_prompt.md` is optional, but if non-empty, must contain only English text
4. `task_config.json` must have non-empty `needed_mcp_servers` and `needed_local_tools` with `claim_done`

## Implemented Tasks

The following tasks are currently in the final pool:

- analytics-dashboard
- cache-optimizer
- certificate-manager
- client-portal
- customer-feedback-processor
- customer-portal
- discount-calculator
- health-monitor
- help-desk
- inventory-management
- log-analyzer
- loyalty-program
- media-organizer
- robots-handler
- scheduler
- sitemap-generator
- social-connector
- status-checker
- storage-manager
- streaming-service
- survey-builder
- sync-service
- tag-manager
- territory-manager
- web-crawler
