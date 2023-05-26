# Zach Thill Helm Charts

This repository was originally created in the attempt to add some more functionality to the now publicly archived helm chart [spark-history-server](https://github.com/helm/charts/tree/master/stable/spark-history-server)

The purpose for making this repository was to add in AWS IAM capabilities for service accounts into this helm chart directly so the spark history server could authenticate to S3 via an IAM role rather than just static keys. For more information regarding how to utilize this helm chart, follow the AWS [documnetation](https://docs.aws.amazon.com/eks/latest/userguide/iam-roles-for-service-accounts.html) for setting up IAM roles for Kubernetes Service Accounts, and the original [README](https://github.com/helm/charts/blob/master/stable/spark-history-server/README.md) file from the public archives.

