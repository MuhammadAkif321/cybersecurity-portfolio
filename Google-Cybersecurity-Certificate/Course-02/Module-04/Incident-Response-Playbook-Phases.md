# Six Phases of an Incident Response Playbook

This reference summarizes the six phases introduced in Course 2, Module 4.

## 1. Preparation

**Purpose:** Make sure the organization is ready before an incident occurs.

Examples:
- Define incident response roles and responsibilities.
- Prepare response procedures and communication channels.
- Ensure relevant tools and logging are available.
- Train employees and response team members.

## 2. Detection and Analysis

**Purpose:** Identify a possible incident and understand what is happening.

Examples:
- Review SIEM alerts and relevant logs.
- Check affected accounts, devices, and systems.
- Compare activity with normal behavior.
- Assess the likely scope and severity.

An alert is a signal that needs investigation; it is not automatically proof of an attack.

## 3. Containment

**Purpose:** Stop or limit the incident so it does not spread or cause more damage.

Examples may include:
- Isolating an affected device from the network.
- Disabling or restricting a compromised account.
- Blocking confirmed malicious communication.

Containment actions should follow approved procedures and consider business impact and evidence preservation.

## 4. Eradication and Recovery

**Purpose:** Remove the threat and restore affected systems to secure operation.

Examples:
- Remove malicious files or unauthorized access mechanisms.
- Address the weakness that allowed the incident.
- Reset compromised credentials where appropriate.
- Restore systems from trusted backups.
- Verify that systems are secure before returning them to normal use.

## 5. Post-Incident Activity

**Purpose:** Learn from the incident and improve future response.

Examples:
- Document the timeline, impact, and actions taken.
- Identify the root cause and contributing weaknesses.
- Record what worked and what did not.
- Recommend improvements to controls, training, and procedures.

## 6. Coordination

**Purpose:** Keep the right people informed and ensure response activities are aligned.

Examples:
- Share relevant updates with the incident response team.
- Notify appropriate management and stakeholders.
- Coordinate technical and business decisions.
- Follow internal and applicable external reporting requirements.

Coordination takes place throughout the incident response process; it is not limited to the end.

---

## Illustrative example: suspicious employee account activity

A SIEM alert reports repeated failed sign-in attempts followed by an unusual successful login to an employee account.

| Phase | Possible team activity |
|---|---|
| Preparation | The organization has an account-compromise playbook, assigned responders, and logging in place. |
| Detection and Analysis | The team reviews authentication logs, timestamps, source information, and account activity to assess whether the login is suspicious. |
| Containment | If compromise is confirmed, responders follow approved procedures to secure the account and limit further access. |
| Eradication and Recovery | The team removes unauthorized access, resets affected credentials as appropriate, checks for persistence, and restores normal access securely. |
| Post-Incident Activity | The team documents the incident, determines how access was compromised, and recommends improvements. |
| Coordination | Responders communicate with relevant IT staff, management, and other authorized stakeholders throughout the process. |

This is a conceptual learning example, not a real incident investigation or a technical lab completed by me.

## Professional takeaway

A playbook helps a response team act consistently under pressure. Effective incident response also depends on evidence, sound judgment, authorization, documentation, and clear communication.