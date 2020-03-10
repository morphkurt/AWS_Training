# Solutions Architect - Professional

* 170 mins
* Questions and Answers are longer and complex
* Reading and comprehension exams

## AWS Accounts

LA AWS Account - [Bookmark](https://linuxacademy.com/cp/courses/lesson/course/2851/lesson/1/module/245)

* Isolated piece 1) Authentication / Authorization and Billing.

> Authenticate by login in
> Once authenticated system can authorize to services via IAM and permission store
> Account root users has full access
> Root user can create IAM users, by default IAM users has no permission
> Blast radius keeping small

* Root user is the only Principal that can authenticate to the account and only principal authorized to do so. 

![](images/accounts_diagram.png "AWS account Authentication /Authorization and Billing")

## Regions, AZ, and Edge Infrastructure

LA AWS Account - [Bookmark](https://linuxacademy.com/cp/courses/lesson/course/2851/lesson/2)

### Region

* Large countries may have multiple regions
* Each region is a isolated block on AWS infrastructure.

### Availability Zone

* Each region has multiple availability zone.
* Isolated within the region to manage isolated failure within the region.
* However close enough to have high performance network between AZ.
* Each AZ has separate network / storage and compute infrastructure.
* Does not help geo political influence.

> Fault isolation domains

### Edge Infrastructure

* Edge location in major cities.
* Storage and compute location.
* Improves the user experience.
* You cannot deploy most services in edge locations.






