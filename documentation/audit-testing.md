# Audit Testing and Evidence

## AUD-OT-201 — Perimeter Architecture

- **Target Control:** CNT-OT-101
- **Frequency:** Semi-annually
- **Testing Steps:**
  1. Extract firewall configuration tables separating corporate IT and industrial OT networks.
  2. Verify that inbound IT-to-OT requests are blocked unless routed through explicitly approved and monitored jump boxes.
  3. Review monitoring records for permitted diagnostic connections.
- **Required Evidence:**
  - Firewall configuration exports
  - Network architecture diagrams
  - Zone and conduit documentation
  - Jump-box session access logs

## AUD-OT-202 — Asset Access Governance

- **Target Control:** CNT-OT-102
- **Frequency:** Quarterly
- **Testing Steps:**
  1. Sample active HMIs and PLCs on the manufacturing floor.
  2. Test whether vendor factory-default credentials are disabled or changed.
  3. Validate that authentication configurations reject unmapped or unauthorized local profiles.
  4. Review access provisioning and credential-management records.
- **Required Evidence:**
  - Industrial Active Directory group policies
  - Password vault configuration screenshots
  - Local account configuration logs
  - Access review records

## AUD-OT-203 — Emergency Isolation Playbook

- **Target Control:** CNT-OT-103
- **Frequency:** Annually
- **Testing Steps:**
  1. Review the latest physical tabletop exercise documentation.
  2. Interview plant operations managers about their responsibilities during network containment.
  3. Verify that identified gaps have assigned owners and due dates.
  4. Confirm approval of updated continuity and incident-response procedures.
- **Required Evidence:**
  - Tabletop exercise attendance sheets
  - Sign-off logs
  - Action-item registers
  - Updated continuity policy approvals
