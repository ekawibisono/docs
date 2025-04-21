# Login with AWS CLI

use `aws configure` in the cli to connect your account for Terraform deployment. You will be prompted to enter the following. See [Creating a Secret Key Pair](creating-a-secret-key-pair.md) for more information.

* AWS Access Key ID: <_your\_access\_key\_id_>
* AWS Secret Access Key: <_your\_secret\_access\_key_>
* Default region name: **us-east-1** Use this, as Terraform has known issues with other regions
* Default output format: json
