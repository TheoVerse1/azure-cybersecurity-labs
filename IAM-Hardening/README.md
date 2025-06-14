# IAM Hardening Project

## Project Goal

Strengthen Identity and Access Management (IAM) security within Azure by applying best practices, reducing attack surface, and enforcing least privilege principles.

## Lab Environment

- Azure Active Directory (Entra ID)
- Azure Subscription (Pay-As-You-Go or Free Trial)
- Azure CLI & Azure Portal

## Hardening Tasks

1. **Baseline Audit**
   - Export users, groups, and roles.
   - Identify overprivileged accounts.
   
2. **MFA Enforcement**
   - Enable Multi-Factor Authentication for all users.
   - Use Conditional Access policies where applicable.
   
3. **Least Privilege Access**
   - Remove unnecessary role assignments.
   - Create custom roles for precise access control.
   
4. **Legacy Authentication Block**
   - Disable outdated protocols (IMAP, POP3, SMTP, etc.).

5. **Privileged Identity Management (PIM)**
   - Activate PIM for managing privileged roles.
   - Require approval and justification for role elevation.

6. **Logging and Monitoring**
   - Enable Azure AD sign-in logs.
   - Integrate with Sentinel for centralized monitoring.

## Deliverables

- Policy JSON files stored in `/policies/`
- Screenshots of configurations stored in `/screenshots/`
- Notes and troubleshooting in `/notes.md`

## References

- [Microsoft IAM Best Practices](https://learn.microsoft.com/en-us/azure/security/fundamentals/identity-management-best-practices)
- [Azure AD Conditional Access](https://learn.microsoft.com/en-us/azure/active-directory/conditional-access/overview)


