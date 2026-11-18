# Final Task Pool

This directory is the final pool containing all tasks whose status is **implemented** on the
Notion "Task Tracker" page (Task Status Table), aggregated from the developer branches
(`fan-dev`, `gyy`, `haoze`, `jl_dev`, `junteng_dev`, `junxian_dev`, `lueyang-dev`, `lv`,
`ruige`, `wenshuo-dev`, `xiaochen_dev`, `yuxuan-dev`, `yuzhen-dev`, `zhaochen`).

## Status: empty

As of the audit on 2026-11-18, **none** of the 116 new developer tasks satisfies the task
requirements defined in `tasks/examples/example-task`:

- every task is missing the required root `task_config.json` (which must contain a non-empty
  `needed_mcp_servers` field and a non-empty `needed_local_tools` field that includes
  `claim_done`);
- in addition, 18 tasks contain non-English (Chinese) text in their required all-English
  documentation (`docs/agent_system_prompt.md` / `docs/task.md`).

Therefore all 116 tasks are marked `implementing` in the Notion Task Tracker and no task
qualifies for the final pool yet. This directory intentionally contains no task folders.
