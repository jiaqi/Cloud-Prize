Edit this page to describe your Submission.

## Which Categories Best Fit Your Submission and Why?

Best Contribution to Operational Tools, Availability, and Manageability

## Describe your Submission

DataMung is a self-serviced tool that runs mysqldump against RDS MySQL database
instance from a copy of EC2 instance, and stores result to S3. It also go
backwards and restore an RDS instance from S3 object. The steps in backup or
restore process is driven by Simple Workflow. User interacts the tool via a
web UI, which calls a RESTful service that allows other systems to integrate
with the tool.

This tool allows user to replicate MySQL instance across regions or accounts.

## Provide Links to Github Repo's for your Submission

https://github.com/jiaqi/datamung