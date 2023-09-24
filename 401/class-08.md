# Access Control (ACL)

Access Control, often implemented using Role-Based Access Control (RBAC), is a crucial aspect of application security. RBAC helps in managing and regulating user access to various resources within an application, ensuring that users can only perform actions for which they have proper authorization.

## 5 steps to RBAC

**What is Role-Based Access Control (RBAC) and why do we care?**

- RBAC is a security model that assigns roles to users, and each role has specific permissions. It's important because it simplifies access management by organizing users into roles, reducing complexity, and enhancing security.

**Describe a Role/Permission hierarchy that you might implement using RBAC.**

- In a web application, you might have roles like 'User,' 'Moderator,' and 'Admin.' 'User' has basic read access, 'Moderator' can edit content, and 'Admin' has full control.

**What approach might you take to implement RBAC?**

- To implement RBAC, you can start by defining roles and permissions, assigning roles to users, and then enforcing access controls based on a user's role and the required permissions.

## wiki - RBAC

**If Authentication is “you are who you say you are,” what is Authorization?**

- Authorization is the process of determining what actions or resources an authenticated user is allowed to access.

**Name three primary rules defined for RBAC.**

1. Role Assignment: Users are assigned roles based on their responsibilities.
2. Role Authorization: Roles have specific permissions associated with them.
3. Role Governance: Regular reviews and updates of role assignments to ensure security.

**Describe RBAC to a non-technical friend.**

- Imagine RBAC as a system where different people in a company wear different badges. These badges determine what they can and cannot do in the office. So, if someone has a 'Manager' badge, they can access certain rooms and files, while someone with a 'Visitor' badge can only enter the lobby. It's like having different levels of access in a video game.

## RBAC tutorial

**What Are access rights Associated with? The User? or The Role? Explain.**

- Access rights are associated with roles. Users are assigned roles, and those roles determine their access rights. So, it's the roles that have access rights.

**Access Rights, or Authorization, is activated after a user successfully does what?**

- Access rights or authorization are activated after a user successfully authenticates, proving their identity through login.

**Explain how RBAC might benefit a business.**

- RBAC benefits a business by improving security and efficiency. It ensures that employees can only access the resources necessary for their roles, reducing the risk of data breaches. It also simplifies access management, making it easier to onboard new employees and adapt to changing organizational needs.

## Reflection

1. What are your learning goals after reading and reviewing the class README?
   - I aim to have the ability to revisit and reference the topics and themes we've covered in the course, considering the extensive content we're learning.

## Things I want to know more about

## Reference

- Reading Materials
- ChatGPT