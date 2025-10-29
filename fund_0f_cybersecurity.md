# Fundamentals of Computer Security
## Identification, Authentication, and AuthorIzation

| Concept             | Description           | Example                             |
|-----------------    |------------------     |---------------------                |
|**Identification**   | Claiming an identity  | Tying username                      |
|**Authentication**   | Proving identity      | Entering password / fingerprint     |
|**Authourization**   | Granting acces        | Accessing certain files after login |

## Key Principle
"Authentication verifies who you are. Authourization decides what you can do."

# Authentication Methods
- Knowledge-based: Passwords, PINS
- Possession-based: Smart cards, OTP tokens
- Inherence-based: Biometrics (fingerprint, face ID)
- Multifactor Authentication (MFA): Combination of 2 or more above
- Single Sign-On (SSO): One-time login across multiple systems (e.g., Google or Microsoft SSO)

# Authorization Models
- DAC (Discretionary Access Control): Owner decides who can access (Windows permissions).
- MAC (Mandatory Access Control): Access based on classification levels (military systems).
- RBAC(Role-Based Access Control): Permissions assigned to roles (Admin, Manager, User).
-ABAC (Attribute-Based Access Control): Access based on conditions (time, location, user type).

## Example:
An "HR manager" role can view employe data,while "Emoloyee" role can only view their own profile

# Best pectices

- Use strong, unique passwords.
- Apply MFA wherever possible.
• Review role-based permissions regularly.
- Log all authentication and access events.
