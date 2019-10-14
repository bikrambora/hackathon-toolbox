---
title: "Build an API"
weight: 10

---

![TAT image](/images/044-network-1.png?width=20%)

## Build an API
```
An api is an interface to connect and talk to another resource on the web
```

### Getting set up

1. Install the AWS CLI using the steps <a href = "https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-install.html">here</a>
   
2. Configure the aws CLI with Credentials as shown <a href = "https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-configure.html" target="_blank">here</a>
```
$ aws configure
AWS Access Key ID [None]: AKIAIOSFODNN7EXAMPLE
AWS Secret Access Key [None]: wJalrXUtnFEMI/K7MDENG/bPxRfiCYEXAMPLEKEY
Default region name [None]: us-west-2 // put in your region
Default output format [None]: json
```

3. Install the aws amplify cli 
```
$ npm install -g @aws-amplify/cli
$ amplify configure
```

4. Familiarise yourself with the CLI commands by having a quick glance at this <a href="https://aws-amplify.github.io/docs/cli-toolchain/quickstart?sdk=js">CheatSheet</a> 