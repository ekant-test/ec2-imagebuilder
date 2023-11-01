# ec2-imagebuilder

This CloudFormation template is used to define and provision various AWS resources for the purpose of creating an Image Recipe and managing AMIs (Amazon Machine Images) using AWS Image Builder and also storing the AMI in SSM paramter store fully automated.

We can do lot of things by using aws provided build components such as,
-amazon-cloudwatch-agent-linux
-amazon-cloudwatch-agent-windows
-aws-cli-version-2-linux
-aws-cli-version-2-windows
-aws-codedeploy-agent-linux
-chocolatey
-docker-ce-linux
-php-7_4-linux
-windows-server-iis

We can also create our own custom build component.

Also we have aws provided test components 
-apt-repository-test-linux : Tests whether the apt package manager is functioning correctly.
-ebs-volume-usage-test-linux
-ebs-volume-usage-test-windows
-inspector-test-linux
-reboot-test-linux
-validate-ssh-public-key-linux
-yum-repository-test-linux

And can create custom test components
