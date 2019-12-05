# Cloud Network Fundamentals

The following CloudFormation templates should be used for the practice portion of the workshop. Take your time to bring up a stack.

These stacks attempt to bring up a web server. You should connect to the web server and view the web page in your browser.

Resolve the issues so you are able to view the web page.

To create a stack, use the following command example:

aws --profile <profile> cloudformation create-stack --stack-name gl-lab-1 --template-body file://practice-<1|2|3>.template.yaml

Where profile is your aws profile if you have any and select either 1, 2 or 3.

