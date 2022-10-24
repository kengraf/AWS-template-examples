# Basic EC2 instance [![Launch Stack](https://cdn.rawgit.com/buildkite/cloudformation-launch-stack-button-svg/master/launch-stack.svg)](https://console.aws.amazon.com/cloudformation/home?region=us-east-2#/stacks/new?stackName=cwlogsexport2s3&amp;templateURL=https://unh-it666-logging.s3.us-east-2.amazonaws.com/artifacts/cloudwatchlogsexport2s3/cwexportlogs2s3-master-template.yaml)


# Full LAMP stack
https://s3.us-east-2.amazonaws.com/cloudformation-templates-us-east-2/LAMP_Single_Instance.template

# aws-ec2-logging

This class exercise is based apon  Veronika Megler's work. [here](https://aws.amazon.com/blogs/mt/how-to-export-ec2-instance-execution-logs-to-an-s3-bucket-using-cloudwatch-logs-lambda-and-cloudformation/)  
Some updating was needed as the AWS platform continues to evolve.

### Running the solution  
Your S3 buckets need to be created prior to launching the stack.  At a minimum your need a writable bucket for your logs.  

To see this solution in operation in us-east-2, choose the “Launch Stack” button&nbsp;below.  

[![Launch Stack](https://cdn.rawgit.com/buildkite/cloudformation-launch-stack-button-svg/master/launch-stack.svg)](https://console.aws.amazon.com/cloudformation/home?region=us-east-2#/stacks/new?stackName=cwlogsexport2s3&amp;templateURL=https://unh-it666-logging.s3.us-east-2.amazonaws.com/artifacts/cloudwatchlogsexport2s3/cwexportlogs2s3-master-template.yaml)
