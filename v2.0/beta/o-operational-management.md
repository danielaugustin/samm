---
business_function : Operations
security_practice : Operational Management
assigned_to       : John (john.dileo@owasp.org) 
complete          : 0%
---

# Overview

| | A: Data Protection | B: System decomissioning / Legacy management |
|:---|:---|:---|
| Maturity 1 - Best-effort activities | Data locations documented | Opportunistic identification of unused applications or services |
| Maturity 2 - Processes in place | Data protection policy established | Decomissioning process in place |
| Maturity 3 - Continuous improvement enforced | Data policy breaches detected and acted upon | Proactive reliable handling of legacy |


# A: Data Protection

## Maturity 1
### Activity
It is identified and captured which applications process and store sensitive data. Production sensitive (esp. personal) data is present only in the production environment.

#### Maturity Questions
##### Q 1
Are security notes delivered with each software release?

**Answer Options**
- Option 1
- Option 2
- Option 3
- Option 4

#### Notes
coverage handled by questions?
you know what you have/process
sensitive and/or under regulatory compliance


## Maturity 2
### Activity
Process for handling sensitive data "within system operations"(?) is established (=data protection policy). Data is consequently protected according to the need-to-know principle. Access to sensitive data is reliably protocoled. 

### Maturity Questions
#### Q 1
Do projects utilize a change management process that’s well understood?

**Answer Options**
- Option 1
- Option 2
- Option 3
- Option 4

#### Notes
explain "reliably protocoled" ?
what about integrity/availability ?
cover data retention ??
cover data offshoring?
depends on organization compliance obligations (link with P&C)
need for more concrete SW related use cases / examples

## Maturity 3
### Activity
Compliance to the data protection policy is regularly checked/audited. There are measures ensuring timely detection of broken data protection mechanisms (e.g., regular delete jobs).

### Maturity Questions
#### Q 1
Are project releases audited for appropriate operational security information?

**Answer Options**
- Option 1
- Option 2
- Option 3
- Option 4

#### Notes
where does the data protection policy come from?


# B: System decomissioning / Legacy management

## Maturity 1
### Activity
Explicit (manual or automated) actions for identification of unused applications are carried out. Results are processed for further actions.

### Maturity Questions
#### Q 1
Are security-related alerts and error conditions documented on a per-project basis?

**Answer Options**
- Option 1
- Option 2
- Option 3
- Option 4

#### Notes
definition of legacy ?
out of date or in need of replacement?
no active development / maintenance?

## Maturity 2
### Activity
If application is decomissioned, also all relevant accounts, firewall rules, data, etc. are deleted according to an established process.

### Maturity Questions
#### Q 1
Do project teams deliver an operational security guide with each product release?

**Answer Options**
- Option 1
- Option 2
- Option 3
- Option 4

#### Notes


## Maturity 3
### Activity
Life state of every software asset and underlying infrastructure is periodically evaluated and EOL is estimated. Switching the application into a legacy state triggers a defined process which also mitigates resulting security risks. Lessons learned process for handling legacy is established. 

### Maturity Questions
#### Q 1
Is code signing routinely performed on software components using a consistent process?

**Answer Options**
- Option 1
- Option 2
- Option 3
- Option 4
