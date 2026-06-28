# Synthetic Case Review

This is a small example of how I would use the playbook in a consulting conversation.

## Workflow Idea

A small outpatient team wants AI help triaging inbound follow-up messages and drafting a short prep summary before the clinician reviews the chart.

## Good Candidate Work

- summarize structured chart context
- classify inbound messages into operational vs clinician-review buckets
- surface missing monitoring tasks
- draft a prep summary for human review

## Work To Keep Out Of Scope

- direct patient advice
- autonomous medication changes
- unsupervised message replies
- silent closure of tasks that contain ambiguity or risk language

## Main Review Questions

- Who owns the final decision for each queue?
- What data is required for a useful summary?
- What failure mode matters most: missed risk, wrong routing, or low trust?
- Can the first pilot use only synthetic or de-identified examples?
- How will the team tell whether the workflow is saving time without creating hidden risk?

## Why This Is A Strong Pilot

This kind of workflow is narrow enough to evaluate and important enough to matter. It also exposes a real consulting judgment skill: deciding where the AI should stop.
