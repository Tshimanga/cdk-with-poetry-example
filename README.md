
# Welcome to a Poetry-Managed CDK Python project!

This is a blank example project for showcasing CDK development with Python & Poetry.

The `cdk.json` file tells the CDK Toolkit to execute your app using poetry.

This project is set up like a standard Poetry project.

You can install the required dependencies with

```
$ poetry install
```

At this point you can now synthesize the CloudFormation template for this code.

```
$ cdk synth
```

To add additional dependencies, for example other CDK libraries, just run 
`poetry add [dependency-name]` like for any other Poetry project.

## Useful commands

 * `cdk ls`          list all stacks in the app
 * `cdk synth`       emits the synthesized CloudFormation template
 * `cdk deploy`      deploy this stack to your default AWS account/region
 * `cdk diff`        compare deployed stack with current state
 * `cdk docs`        open CDK documentation

Enjoy!
