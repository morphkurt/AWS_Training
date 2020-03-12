# AWS Accounts

LA Network OSI Model- [Bookmark](https://linuxacademy.com/cp/courses/lesson/course/4047/lesson/1/)

## IAM - Identity Access Manager

* Allows to access control AWS services and resource. 
* Provides Identity Management.

- Users
- Groups 
- Roles
- IAM Policies
- Authentication attributes.

> Allows to maintain IAM Users.
> Can have attached configuration.
> IAM needs to verify user (say who you are) Authentication 
> How? Using UN/PW and access key.
> Secret part of the access key is *only generated once*
> These are known long term access credentials (UN/PW and Access Keys)
> Can have MFA.
> IAM users granted permission using policies directly to user or groups.
> Users and Roles are known as real identities (Both have Amazon resource name ARN )
> Groups are just org or admin construct.
> Configure account wide password policies.

* By default IAM users have no permissions applied. Default IAM has implicit Deny.
* For all users (except root user) permission must be given that grant access to AWS services.
* Deny will always override Allow.

IAM provides identity services - coordinates with STS
There is 5000 IAM user limit per account. However you can use STS to enable identity federation.








