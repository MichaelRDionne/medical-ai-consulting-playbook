# Model Evaluation Checklist

## Workflow Fit

- What human task is being supported?
- What decision remains with the human?
- What would make the output unsafe or misleading?
- What information is intentionally out of scope?

## Output Quality

- Does the output cite or describe its inputs?
- Does it surface missing information?
- Does it avoid making clinical decisions autonomously?
- Does it produce a usable next-action queue?

## Safety

- Are escalation conditions explicit?
- Can a reviewer correct or reject the output?
- Are audit trails preserved?
- Are synthetic demos separated from production data?

## Adoption

- Does the tool save time in a real workflow?
- Does it reduce ambiguity?
- Does it increase review burden?
- Can non-technical stakeholders understand the output?
