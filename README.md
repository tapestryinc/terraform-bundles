# terraform-bundles
Terraform bundle with Validate

The Custom Validate Provider is used today with the tagging module to enforce tagging requirements. For TFE to use this provider, a custom package containing the Terraform version and the validate provider is needed. 
This package needs to be available for TFE to access. For now, TFE is configured to read this public repo. Once the dependency on the validate provider is removed, this repo can be deleted.
