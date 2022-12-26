# IAM

## Users, Permission and Access

- Study the diagram carefully to know about best practices.

![IAM](../Images/IAM1.png)

## IAM User

- IAM User is identity that you can crete in AWS which has name and credentials.
- It represents either the person or application that interacting AWS services.
- You should create individual IAM users for each person who needs to access AWS even if you have multiple employees who require the same level of acces.
- Tags are used to facilitate attribute-based access control for IAM users. It allows access to resources to be granted based on an attribute with an entity. This feature is useful where the access required is temporary or project-based.

## IAM Policies

- An IAM policy is a document that allows or denies permission to AWS services and resources.
- IAM policies enable you to customize users’ levels of access to resources.
- It is recommended the security principle of least privilege when granting permissions.

![IAM Policies](../Images/IAM2.png)

