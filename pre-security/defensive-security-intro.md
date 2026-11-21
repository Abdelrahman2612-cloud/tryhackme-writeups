# Defensive Security Intro

**Platform:** TryHackMe | **Path:** Pre-Security  
**Room:** [Defensive Security Intro](https://tryhackme.com/room/defensivesecurityintro)

## Goal
Learn how defenders monitor systems, investigate suspicious activity, and limit the impact of security incidents.

## Key concepts
- **SOC:** A Security Operations Center is the people and process that monitor an organisation's systems, triage alerts, and coordinate a response. An alert is a lead to investigate, not proof on its own.
- **Threat intelligence:** Useful context about likely adversaries and their behaviour helps defenders decide what activity to watch for and how to prepare. It should be kept current as new evidence appears.
- **SIEM:** A Security Information and Event Management system brings security events from different sources into a place where analysts can search, compare, and spot unusual patterns. Analysts still need to check the surrounding activity before deciding what an alert means.
- **DFIR:** Digital forensics is the careful collection and analysis of evidence such as files, memory, system logs, and network records. Incident response is the organised work of preparing for incidents, detecting and assessing them, containing harm, removing the cause, restoring systems, and recording lessons afterward.
- **Malware analysis:** Static analysis inspects a suspicious file without running it. Dynamic analysis observes it in a controlled, isolated environment. The goal is to understand behaviour safely, not to execute unknown software on a normal machine.

## Commands / tools
- The practical uses a SIEM-style monitoring dashboard. The useful workflow is to open a notable event, identify the account, device, or network address involved, review related events for context, and escalate or contain it through the team's process.
- No terminal commands are needed for the introductory practical.

## What I learned
Defensive work depends on noticing patterns in data, then checking evidence before acting. A careful analyst records what happened, limits further damage, and uses the investigation to improve future detection and response.

## Reference
- [TryHackMe: Introduction to Defensive Security](https://tryhackme.com/module/introduction-to-defensive-security)
