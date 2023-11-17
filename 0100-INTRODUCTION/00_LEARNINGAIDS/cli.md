# Set up cli 

```bash
aws configure --profile iamadminprod
aws configure --profile iamadmingeneral
```

# use profile locally while running cli command
```bash
aws s3 ls --profile iamadminprod
```