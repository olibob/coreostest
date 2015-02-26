### CoreOS on EC2

The CloudFormation template used is based on the one provided on the CoreOS site.

The only change done so far is an extension of the root fs to 20GB. 8GB is too little for extended tests.

The CloudFormation template is located [here](https://s3-eu-west-1.amazonaws.com/bobcoreos/coreos_template.json) (Bob's S3)

**TODO**

- change the CloudFormation JSON file to reflect the changes done in user-data