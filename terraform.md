## Terraform
- configuration and orchestration management tool
- Works and with any cloud; public, private or hybrid
- Terraform concentrates on server provisoning
- The whole cloud infrastructure is treated as code and all the parameters are combined in a delcarative configuration files.

## Immutable infrastructure
- It is the practice of provisioning a new server for every config change and de-provisioning old ones. Provisioning tools like Terraform and CloudFormation support the creation of immutable infrastructure to a great extent. For every software configuration change, these tools help to create new infrastructure and deploy the new configuration before deleting the old one. This helps to manage large infrastructure, as we do not need to worry about the configuration changes and their impact over a period of time.

## Benefits of Immutable infrastructure
- immutable infrastructure is consistent and reliable, which makes testing more straightforward.
- Deployment is simpler and more predictable.
- Each deployment is versioned and automated, so environment rollback is a breeze.
- Errors, configuration drifts, and snowflake servers are mitigated or eliminated entirely.
- Deployment remains consistent across all environments (dev, test, and prod).
- Auto-scaling is effortless thanks to cloud services.
