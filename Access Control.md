## Access Control
#### What is Role Based Access Control (RBAC) and why do we care?   
***
>An extensively employed access control mechanism that offers a systematic method for overseeing permissions and access privileges in an organization's systems or applications. Roles establish a collection of permissions and privileges linked to distinct job functions or responsibilities within the organization. Permissions delineate the actions or operations permitted on a specific resource or system.


#### Describe a Role/Permission heirarchy that you might implement using RBAC.
***
**Role: Guest**

**Permissions: View products Register as a new user Add products to the cart**

**Role: Customer**

**Permissions: All permissions of the Guest role Purchase products Manage user profile**

#### What approach might you take to implement RBAC?
*** 
**Identify Roles, Determine Permissions, Assign Permissions to Roles, Map Users to Roles, Implement Access Control**

### If Authentication is “you are who you say you are,” what is Authorization?
***
**It entails the act of allowing or denying access to particular actions, operations, or resources based on the authenticated user's privileges or permissions.**

### Name three primary rules defined for RBAC.
***
**Role Assignment, Role Authorization, Role Permissions**
### Describe RBAC to a non-technical friend.
***
>RBAC is a method that assigns roles to individuals based on their job responsibilities, granting specific access permissions accordingly. This system enhances security by restricting unauthorized access to sensitive areas or information, ensuring that people can only access what is necessary for their work.

### What Are access rights Associated with? The User? or The Role? Explain.
***
>associated with roles, not individual users. In RBAC, permissions and access privileges are defined at the role level, and users acquire those permissions by being assigned to specific roles.

### Access Rights, or Authorization, is activated after a user successfully does what?
***
**After successful authentication, RBAC assigns users specific roles and access permissions, enhancing security and limiting unauthorized access to sensitive areas or information.**

### Explain how RBAC might benefit a business.
***
**RBAC offers several benefits, including enhanced security, improved access control, compliance and auditability, and increased productivity.**