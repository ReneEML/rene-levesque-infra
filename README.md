# Infra for [renelevesque.com](https://renelevesque.com)
- Route 53 pointing to cloudfront distibution
- Cloudfront distribution pointing to S3 bucket
- S3 bucket to hold static website files
- SSL certificate
# Commands to run

- `terraform init` - To initialise the project and download any required packages.
- `terraform plan` - To see what has changed compared to your current configuration.
- `terrform apply` - To apply your changes.

# Resources
- [Template](https://github.com/alexhyett/terraform-s3-static-website)
- [AWS Guide](https://docs.aws.amazon.com/AmazonS3/latest/userguide/website-hosting-custom-domain-walkthrough.html#root-domain-walkthrough-configure-redirect)
- [Cloudfront Guide](https://docs.aws.amazon.com/AmazonS3/latest/userguide/website-hosting-cloudfront-walkthrough.html)
- [Terraform Docs](https://registry.terraform.io/providers/hashicorp/aws/latest/docs)
