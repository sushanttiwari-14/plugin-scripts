# Groovy trigger QA evidence

Kestra 1.3.39 with plugin-script-groovy 1.13.1-SNAPSHOT and groovy:jdk21.

- 01-script-trigger.jpg: user-supplied ScriptTrigger log view with the bottom chat overlay removed. The original capture is preserved in 01-script-trigger-original.png. Visible flow, execution ID, statuses, and log values match the original.
- 02-commands-trigger.png: user-captured CommandsTrigger log view.

Both executions were checked through the local API and have trigger type ScriptTrigger or CommandsTrigger, respectively. The logs show downstream access to condition, exitCode, status, and count. The images contain no credentials or unrelated chat.

This branch contains only QA evidence, separate from the feature source diff.
