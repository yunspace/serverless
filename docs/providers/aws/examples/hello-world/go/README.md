<!--
title: Hello World Go Example
menuText: Hello World Go Example
description: Create a Go Hello World Lambda function
layout: Doc
-->

<!-- DOCS-SITE-LINK:START automatically geneated  -->
### [Read this on the main serverless docs site](https://www.serverless.com/framework/docs/providers/aws/examples/hello-world/go/)
<!-- DOCS-SITE-LINK:END -->

# Hello World C# Example

Make sure `serverless` is installed. [See installation guide](../../../guide/installation.md).

## 1. Create a service
`serverless create --template aws-go --path myService` or `sls create --template aws-go --path myService`, where 'myService' is a new folder to be created with template service files.  Change directories into this new folder.

## 2. Build using go build and create a static binary

```
# Linux or OSX
./build.sh
```

```
# Windows PowerShell
./build.cmd
```

## 3. Deploy
`serverless deploy` or `sls deploy`. `sls` is shorthand for the Serverless CLI command

## 4. Invoke deployed function
`serverless invoke --function hello` or `serverless invoke -f hello`

`-f` is shorthand for `--function`

In your terminal window you should see the response from AWS Lambda

```bash
{
    "message": "Go Serverless v1.0! Your function executed successfully!"
}
```

Congrats you have just deployed and run your Hello World function!
