# Illustrative Security Monitoring Scenario

<sub>Educational example — not a real incident, production investigation, or completed hands-on lab.</sub>

## Scenario

A company operates an online store. Its environment includes employee accounts, web servers, and a network protected by a firewall. The company collects logs from these systems and sends relevant data to a SIEM platform.

One morning, the SIEM dashboard shows a noticeable increase in failed sign-in attempts against an employee account. Around the same period, firewall logs show repeated connection attempts from an unfamiliar external address.

These events do not prove that an account has been compromised. They are signals that may deserve investigation.

## How the log sources can help

| Data source | Example information | Why it matters |
|---|---|---|
| Authentication or server logs | Repeated failed sign-ins, account name, timestamps | May reveal password-guessing activity or a user having trouble signing in |
| Firewall logs | Allowed or blocked connections, source and destination addresses, timestamps | May show repeated or unusual network connections |
| Network logs | Connection patterns and communication between systems | May help determine whether related systems were contacted |

The exact fields available depend on the organization's systems and logging configuration.

## How a SIEM can support the investigation

1. **Collect:** Gather relevant events from the available log sources.
2. **Correlate:** Compare timestamps, account details, and network information to see whether the events may be related.
3. **Alert:** Notify the security team when activity matches a configured detection rule or threshold.
4. **Review:** An analyst checks the alert, supporting events, and normal activity to assess whether it is suspicious.
5. **Escalate or close:** If evidence supports a security incident, follow the organization's incident response process. If the activity is legitimate, document the reason and close or tune the alert as appropriate.

## Example response considerations

If investigation indicates a genuine attack, the response team may consider actions such as securing the affected account, reviewing related activity, blocking confirmed malicious traffic, and checking whether other systems were affected. Actions should follow the organization's approved procedures and authorization requirements.

A playbook can guide the response steps. A SOAR platform may automate selected tasks, such as enriching an alert with additional information or creating an incident ticket.

## Professional learning points

- One alert is not automatically proof of an attack.
- Logs from different sources can provide complementary evidence.
- Accurate timestamps and useful log fields support event correlation.
- SIEM dashboards help prioritize attention, but analysts must validate alerts.
- Incident response should follow documented procedures and preserve relevant evidence.

## Scope note

This is a conceptual example created to demonstrate how the module's topics can apply to a business environment. No actual logs were collected, no SIEM platform was configured, and no real incident was investigated.