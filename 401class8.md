[Home](/README.md)

# Class 8 - Access Control (ACL)

## 5 steps to RBAC

1. What is Role Based Access Control (RBAC) and why do we care?  
RBAC involves assigning system access to employees based on their role in an organization. This approach makes access management more efficient and systems more secure.
1. Describe a Role/Permission heirarchy that you might implement using RBAC.  
Administrators: full access to all resources and actions; HR Staff: access to and ability to modify employee information; Employees: access to ability to modify their own information.
1. What approach might you take to implement RBAC?  
To implement RBAC we would identify each role and the permissions required to perform the role. Access would be granted and restricted based on the role.

## wiki - RBAC

1. If Authentication is “you are who you say you are,” what is Authorization?  
Authorization is the process of granting or denying access to resources and actions based on a user's role and permissions. It follows the authentication process.
1. Name three primary rules defined for RBAC.  

>1. Role assignment: A subject can exercise a permission only if the subject has selected or been assigned a role.
>2. Role authorization: A subject's active role must be authorized for the subject. With rule 1 above, this rule ensures that users can take on only roles for which they are authorized.
>3. Permission authorization: A subject can exercise a permission only if the permission is authorized for the subject's active role. With rules 1 and 2, this rule ensures that users can exercise only permissions for which they are authorized.

1. Describe RBAC to a non-technical friend.  
RBAC is a process of controlling access to resources and actions in a system, based on a user's role within the organization. Users only access information they need to perform their jobs, improving security and protecting sensitive information.

## RBAC tutorial

1. What Are access rights Associated with? The User? or The Role? Explain.  
Access rights are associated with the role. Users can access resources and actions based on what their roles necessitate.
1. Access Rights, or Authorization, is activated after a user successfully does what?  
Authorization is activated after a user authenticates themselves and they are activated into a role.
1. Explain how RBAC might benefit a business.  

- Improved efficiency in policy implementation
- Improved security and accountability

## Reflection

1. What are your learning goals after reading and reviewing the class README?  
Understand and implement Access Control
