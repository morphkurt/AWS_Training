# High Availability, Fault Tolerance and Disaster Recovery

LA AWS Account - [Bookmark](https://linuxacademy.com/cp/courses/lesson/course/2851/lesson/3)

![](images/architecture_principle.png "High Availability, Fault Tolerance and Disaster Recovery")
## HA 

Ability recover from a failure

> Example 4x4 with a spare wheel, using the spare wheel recover from failure.
> Auto scaling group in multiple AZ.

## Fault Tolerance

> Example plane with multiple engine.
> FT system needs to survive failures.
> Example RDS database to manage data integrity
> System works through failure.

## DR

Separate process outside of HA and FT. A different system protects critical system data and recreate the system.

# RPO and RTO

LA RPO and RTO - [Bookmark](https://linuxacademy.com/cp/courses/lesson/course/2851/lesson/4)

![](images/rto_rpo.png "High Availability, Fault Tolerance and Disaster Recovery")

## RPO - Recovery Point Objective

* When disaster occurs and the last recoverable backup is.
* Amount of data lose.


## RTO - Recovery Time Objective

* Time from disaster occurs and time to recover the platform.

# Data Persistance

LA Data Persistance - [Bookmark](https://linuxacademy.com/cp/courses/lesson/course/2851/lesson/5)

## Ephemeral

Data is local to resource, the data is lost when resources are turned off. (ie: RAM drive / instance store)

> fastest storage.

## Transient

Type of storage used within Software development architecture. Injected into memory where other services will use that memory.

(ie: SQS )

## Persistent

EBS
S3
EFS