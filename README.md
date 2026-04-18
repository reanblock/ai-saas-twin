# Digital Twin

Taken from AI in production course [here](https://github.com/ed-donner/production/blob/main/week2/day4.md#day-4-infrastructure-as-code-with-terraform).

## Initialize Terraform

```bash
cd terraform
terraform init
```

## Build and deploy

The following will deploy the app to a `dev` environment.

```bash
./scripts/deploy.sh dev
```