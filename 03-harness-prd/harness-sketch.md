# Harness Sketch

Describe Juno's role and task: Juno PM is an AI Associate Product Manager for RocketShip. For this prototype, Juno's job is to solve "Signal Collapse" by synthesizing signals from across the company and producing a concise"What Changed This Week?" briefing for Product Managers. Instead of making decisions, Juno helps PMs understand what needs attention so they can make faster, better-informed decisions.

_Rough first pass, Module 3 Lab 1. Not the AI PRD._

## 01 · Context
Juno can see:
- Support tickets and customer escalations
- Jira bugs and feature requests
- Slack discussions
- Sales notes and blocked deals
- Product roadmap status
- Engineering capacity constraints
- Company strategy priorities

Juno uses this context to determine which issues are emerging, which customers are affected, and which signals deserve attention in the weekly briefing. The project brief describes Juno as operating inside Slack, Notion, and Jira to synthesize scattered signals into insight.

## 02 · Tools
Juno can:
- Aggregate signals from multiple sources
- Group related signals into themes
- Identify trends and recurring issues
- Generate a weekly summary
- Highlight risks and customer impact
- Recommend areas for PM review
- Link findings back to source evidence

Juno cannot:
- Commit roadmap changes
- Promise delivery dates
- Reprioritize work automatically
- Make customer commitments
- Override PM decisions

Juno is an assistant that supports judgment rather than replacing it.

## 03 · Loop
2 attempts
- Analyze incoming signals and generate themes.
- Re-cluster or refine results if confidence is low or signals conflict.

After that, Juno presents the summary to the PM rather than continuing autonomously.

## 04 · Memory
Juno remembers:
- Previously identified themes
- Open risks
- Major escalations
- Historical trends
- Past weekly briefs

This allows Juno to recognize whether an issue is new, recurring, improving, or getting worse over time.

## 05 · Permissions
Juno may automatically:
- Read and synthesize approved data sources
- Generate weekly briefings
- Highlight emerging risks
- Group signals into themes
- Surface supporting evidence
- Notify a PM when a significant trend emerges

Juno must ask for human approval before:
- Changing priorities
- Recommending roadmap commitments
- Communicating with customers
- Escalating severity levels
- Making resource allocation decisions

Because Juno influences roadmap, customer, and engineering discussions, final judgment remains with the human Product Manager.

## 06 · Verification
Juno checks:
- Every reported theme is supported by one or more underlying signals.
- Escalations and high-impact customer issues are included in the summary.
- Recommendations are linked to source evidence.
- No themes are invented without supporting data.
- The generated briefing aligns with RocketShip's goal of helping PMs answer questions faster and reduce Signal Collapse.

Verification output:
- Confidence: High / Medium / Low
- Number of supporting signals per theme
- Links to source tickets, Slack discussions, or escalations
- Any gaps or missing context requiring PM review

Human validation: A Product Manager reviews the briefing and confirms:
"Does this accurately represent the most important things that changed this week?"

If yes, Juno's output is considered successful. Formal metrics and evaluation criteria will be defined later in the project when impact measurement is introduced.
