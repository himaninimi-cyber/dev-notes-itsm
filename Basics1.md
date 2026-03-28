# 📌 HIMANI — CLOUD + INCIDENT TRAINING NOTES

---

# 🧠 DAY 1 — SYSTEM BASICS

## System
A system is a group of components working together to perform a function.

## Client
Client requests data or service.

## Server
Server provides data or service.

## Request & Response
Request = asking for something  
Response = receiving the answer  

Flow:
Client → Request → Server → Response → Client

## Middle Layer
Receives, processes, and forwards requests between client and server.

👉 Can act as both:
- Server (to client)
- Client (to server)

## Web Server vs App Server
- Web Server → serves content
- App Server → processes logic

## Golden Line
Client asks → Middle processes → Server provides

---

# 🧠 DAY 2 — INCIDENT BASICS

## Incident
An incident is any unplanned interruption or degradation of an IT service.

## Types of Incidents
- Critical → System down
- Performance → Slow system
- Functional → Feature not working
- Access → User cannot access

## Severity Levels
- P1 → Critical (high impact)
- P2 → High (major issue)
- P3 → Medium (manageable)
- P4 → Low (minor issue)

👉 Severity = Impact + Urgency

## Incident Lifecycle
1. Identification
2. Logging
3. Initial Diagnosis
4. Investigation / Escalation
5. Resolution
6. Closure

---

# 🧠 DAY 3 — TROUBLESHOOTING MINDSET

## Layered Thinking (VERY IMPORTANT)
Client → Network → Server → Application → Database

## Golden Rule
Never jump layers — go step by step.

---

## Breaking Problems
Big problem → break into small parts

Example:
Website not working:
- Client issue?
- Network issue?
- Server issue?
- App issue?
- DB issue?

---

## Troubleshooting Cheat Sheet

### Core Flow
Understand → Scope → Client → Network → Server → App → Logs → Fix → Confirm

---

## Step-by-Step

1. Understand Issue
2. Check Scope (1 user vs many)
3. Client Check (internet, device, credentials)
4. Network Check (DNS, firewall)
5. Server Check (CPU, memory, disk)
6. Application Check
7. Logs Analysis
8. Fix or Escalate
9. Confirm & Close

---

## Ultra Short Memory

Client → Network → Server → App → Logs → Fix

---

## Login Issue Layers

Login issue can belong to:
- Client (credentials)
- Network (DNS/firewall)
- Server (auth service)
- Application (login feature)
- Database (user data)

---

## Thinking Under Pressure

### Rules
- Don’t assume → Verify
- Don’t jump → Follow layers
- Don’t panic → Break problem

---

## Interview Golden Answer

“I will first understand the issue and check whether it is affecting one or multiple users. Then I will rule out client-side issues like internet or device problems. After that, I will verify network connectivity, followed by checking server health such as CPU, memory, and disk. Then I will check application behavior and review logs to identify the root cause. Based on findings, I will resolve the issue or escalate if needed. Finally, I will confirm with the user and close the incident.”

---

# 🚀 FINAL MINDSET

- Think step-by-step
- Stay calm
- Focus on root cause
- Always confirm before closing
