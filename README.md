This project shows how to connect GitHub Actions to AWS using two methods:
Option A (OIDC), which is the recommended and secure way using an IAM role without storing any access keys, and Option B (Access Keys), which uses IAM user keys saved in GitHub Secrets.
It also includes using a protected prod/dev environment in GitHub so deployments require approval.
