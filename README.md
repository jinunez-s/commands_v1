# commands_v1

# crear cdk
* `cdk init --language typescript`

# Packages Install
* `npm i @aws-sdk/client-eventbridge`
* `npm i @aws-sdk/types`
* `npm i @aws-cdk/aws-lambda @aws-cdk/aws-dynamodb @aws-cdk/aws-apigateway`
* `npm i typescript@5.1.3 ts-node jest ts-jest @types/node @types/jest --save-dev`
* `npm i @aws-sdk/client-dynamodb`

# CDK Commmands
* `cdk deploy`      deploy this stack to your default AWS account/region
* `cdk diff`        compare deployed stack with current state
* `cdk synth`       emits the synthesized CloudFormation template
* `cdk bootstrap`   (one Time) is the process of provisioning resources fot the AWS CDK before you can deploy AWS CDK apps into AWS Enviorment

# npm Commands
* `npm i esbuild`
* `npm run build` Creates a build directory with a production build of your app

# Typescript
* `npm init -y` Initializing typescript project

# DynamoDB ver tablas
* `aws dynamodb list-tables --endpoint-url http://localhost:8000`

# Create Jest configuration
* `npx ts-jest config:init` --> This create a basic Jest configuration file which will inform Jest about ho to handle .ts files correctly
* `npx jest`: To test all files in test folder
* `npx jest .\test\email-sender.test.ts -t "Send Email"`: to test an especific file
* `npx jest --coverage`: Stats
* `npm run build`   compile typescript to js
* `npm run watch`   watch for changes and compile
* `npm run test`    perform the jest unit tests
  

# Install CDK first time in PC
* `npm install -g aws-cdk`           install latest version
* `npm install -g aws-cdk@x.yy.z`    install specific version

# Imports
* `import * as s3 from 'aws-cdk-lib/aws-s3'`                                S3Bucket
* `import * as dynamodb from 'aws-cdk-lib/aws-dynamodb'`                    DynamoDB
* `import * as lambda from 'aws-cdk-lib/aws-lambda'`                        lambda
