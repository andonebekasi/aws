# aws
template terraform


Note:

jalanin script


source jalan.sh
source jalan-default-vpc.sh

- aws ec2 create-default-vpc
 ( https://docs.aws.amazon.com/vpc/latest/userguide/default-vpc.html )
- export AWS_ACCESS_KEY_ID="NUHKOIJFOJF9GFJDO" 
  
  export AWS_SECRET_ACCESS_KEY="LSDJKFODSJF9SDJF8UH3U3HFKW"
  ( https://www.agix.com.au/build-an-ec2-using-ansible-step-by-step/ )

- aws sts get-caller-identity
  ( http://www.hosty.uk/aws/finding-an-ami-id-using-aws-cli-in-aws-marketplace/ )
 
- https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/finding-an-ami.html
- https://geekdudes.wordpress.com/2018/01/05/deploying-amazon-ec2-instance-using-terraform/
- https://aws.amazon.com/blogs/compute/query-for-the-latest-amazon-linux-ami-ids-using-aws-systems-manager-parameter-store/
- http://2ninjas1blog.com/terraform-assigning-an-aws-key-pair-to-your-ec2-instance-resource/
- https://docs.aws.amazon.com/cli/latest/reference/ec2/describe-instances.html

- aws configure
  https://tunnelix.com/deploy-aws-ec2-instances-using-ansible/
- https://registry.terraform.io/modules/terraform-aws-modules/vpc/aws/2.7.0/examples/manage-default-vpc
- https://ifritltd.com/2017/12/06/provisioning-ec2-key-pairs-with-terraform/
- https://www.bogotobogo.com/DevOps/Terraform/Terraform-terraform-userdata.php
- https://www.bogotobogo.com/DevOps/Terraform/Terraform-VPCSubnet-ELB-RouteTable-SecurityGroup-Apache-Server-1.php
- https://medium.com/@aliatakan/terraform-create-a-vpc-subnets-and-more-6ef43f0bf4c1

- https://blog.gruntwork.io/an-introduction-to-terraform-f17df9c6d180
- https://linoxide.com/devops/install-terraform-provision-aws-ec2-instance/


====

Examples
Allowing everyone to execute the script, enter:

chmod +x script.sh
OR

chmod 0755 script.sh
Only allow owner to execute the script, enter:

chmod 0700 script.sh
OR

chmod u=rwx,go= script.sh
OR

chmod u+x script.sh
To view the permissions, use:

ls -l script.sh

https://bash.cyberciti.biz/guide/Setting_up_permissions_on_a_script

