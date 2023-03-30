# IaC for KyberKorp

To create this TF state

```console
export AWS_ACCESS_KEY_ID=(your access key id)
export AWS_SECRET_ACCESS_KEY=(your secret access key) 
```

or

```console
set AWS_ACCESS_KEY_ID=(your access key id)
set AWS_SECRET_ACCESS_KEY=(your secret access key)
```

cd shared

comment the contents of the `_backend.tf` file and save.

```console
terraform init
terraform apply
```

the new S3 bucket should be created.  Uncomment the contents of the `_backend.tf` file and save.

```console
terraform init
```

type `yes` to move the terraform state to the newly created S3 bucket.

