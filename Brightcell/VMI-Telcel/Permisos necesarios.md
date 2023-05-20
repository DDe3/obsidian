## Para lambda

Es necesario un rol que pueda acceder a:
- [x] Bucket [brightcell-nonprod-vmi-telcel](https://s3.console.aws.amazon.com/s3/buckets/brightcell-nonprod-vmi-telcel?region=us-east-1).
- [x] Base de datos en instancia EC2.
- [ ] Secret Manager (crear uno).

## Para Glue Job

Es necesario **modificar** un rol para que pueda acceder a:
- [x] Bucket: [brightcell-nonprod-vmi-telcel](https://s3.console.aws.amazon.com/s3/buckets/brightcell-nonprod-vmi-telcel?region=us-east-1)

## Para IAM

Es necesario los permisos:
- [x] iam:AttachRolePolicy
- [x] AmazonVPCReadOnlyAccess
- [ ] Failed to fetch a list of secrets
