# IAM Hardening Notes

## Initial Audit

- Exported list of users and roles.
- Found multiple users with Owner role - flagged for review.
- Service principals missing proper naming convention.

## MFA Configuration

- Enabled MFA via Conditional Access.
- Applied policy to All Users excluding break-glass accounts.

## Role Adjustments

- Removed Owner role from standard users.
- Assigned custom Reader + Contributor roles to limited groups.

## Legacy Auth

- Disabled legacy authentication protocols via Conditional Access.

## Privileged Identity Management (PIM)

- Enabled for Global Administrator and Security Administrator roles.
- Set up notifications and approval workflows.

## Challenges

- Some third-party apps required legacy auth exceptions.
- Licensing limitations on trial subscription for PIM.

## Next Steps

- Regularly review role assignments.
- Implement Just-In-Time access for administrative roles.
- Integrate with Sentinel for ongoing monitoring.

