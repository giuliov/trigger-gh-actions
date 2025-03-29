# trigger-gh-actions

Play with triggers and conditions.

# CI -> CD

## Using workflow_run

`github.ref` & `github.sha` are the same as the triggering workflow.  
Use `github.event.workflow_run` to know about the triggering workflow.
