# 401 Reading Notes 8 - Access Control (ACL)

[5 steps to RBAC](https://www.csoonline.com/article/3060780/security/5-steps-to-simple-role-based-access-control.html)

1. What is Role Based Access Control (RBAC) and why do we care?
RBAC is the idea of assigning system access to users based on their role within an organization. We care, because it provides additional security in order to avoid 
having compromised credentials by hackers. 

2. Describe a Role/Permission heirarchy that you might implement using RBAC.
A simple hierarchy might look like the following:

Basic -- no access to certain files
Admin -- access to everything

3. What approach might you take to implement RBAC?

The article suggests taking the following 5 steps to implement RBAC.

1. Inventory your system -- make a list of the data and systems you need to control access to (e.g. e-mail, databases, important folders on a server)
2. Analyze your workforce and create roles -- look for common patterns of who needs access to what and define simple roles
3. Assign people to roles
4. Never make one-off changes - do not make exceptions for a single user; if necessary create new roles.
5. Audit -- take a look at the roles, the people assigned to them and the permissions they have and update as necessary.


[wiki - RBAC](https://en.wikipedia.org/wiki/Role-based_access_control)

1. If Authentication is “you are who you say you are,” what is Authorization?

Authorization in contrast refers to the access permissions you have-- "Are you allowed to do the thing you're asking to do?"

2. Name three primary rules defined for RBAC.
The three primary rules defined are:

Role assignment: A user can only use a permission if they have been assigned a role.
Role authorization: A user can only take on roles they are authorized for.
Permission authorization: A user can use a permission only if the permission is authorized for the user's active role(s).

3. Describe RBAC to a non-technical friend.
RBAC is a way to secure a user system (typically at a company) by limiting access to users based on their role in the system. 
For example, from my experience in the military, it has a very structured hierarchal approach to where only certain individuals
have access to classified files. The role of the admin has the capability of accessing certain classified files which hold private information of 
individuals who work in the military. I know, because I've worked side-by-side with an admin before and helped organize such classified files.

## Videos
[RBAC tutorial](https://www.youtube.com/watch?v=C4NP8Eon3cA)

1. What Are access rights Associated with? The User? or The Role? Explain.
Access rights are associated with the role and not the user. This is by design of RBAC, which strives to keep us from defining permissions per user but instead by common roles. In this way, we can update the permissions for a role and all users assigned / have permissions for that role will be updated as opposed to updating users individually. For example, in the military, we have a person whose role is to be in charge of maintaining government equipment. When he is replaced, his role
and authority moves onto the next individual. 

2. Access Rights, or Authorization, is activated after a user successfully does what?
Access rights is activated after a user is successfully authenticated.

3. Explain how RBAC might benefit a business.
In most cases, RBAC can benefit businesses because everyone should not have access to everything within a system. For example, a company with a secret recipe or confidential product information would likely want to limit access to very few people, while other information like salary might be more open but still limited to higher management and HR.

## Reflection
1. What are your learning goals after reading and reviewing the class README?
To learn how to implement RBAC through code.
