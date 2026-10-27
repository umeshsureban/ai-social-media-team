# Needs your OK

Items waiting for an owner decision. Agents add items at the bottom of "Open". Only the owner
ticks a box. After ticking, tell the orchestrator: "Process my approvals in queue/needs-your-ok.md."
URGENT items go at the top of "Open". OVER CAP in a title means the spend would pass owner/budget-cap.md.

## Format for every item

    ### Q-YYYYMMDD-NN: <short title>
    - [ ] Approve
    - [ ] Reject
    - What: <what will happen if you approve, in one line>
    - Why it waits: <the rule from owner/approval-bar.md or CLAUDE.md>
    - File: <drafts/... path>
    - Spend: <amount and channel, or none>
    - Requested by: <agent> for brief <B-YYYYMMDD-NN>
    - Owner note: <write here if you reject or want a change>

## Open

### Q-20261026-01: Reply to a one-star review on Google Business Profile (EXAMPLE, delete me)
- [ ] Approve
- [ ] Reject
- What: post the drafted public reply to a one-star review about a long wait at the counter.
- Why it waits: any reply to a negative review always waits (owner/approval-bar.md).
- File: drafts/2026-10-26-gbp-reply-long-wait-review.md
- Spend: none
- Requested by: reviews-reputation for brief B-20261026-01
- Owner note:

## Done
