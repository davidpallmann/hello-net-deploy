# Hello, .NET Deploy!

This is the code project for the [Hello, .NET Deploy!](https://davidpallmann.hashnode.dev/hello-net-deploy) blog post. 

This episode: AWS .NET Deployment Tool. In this Hello, Cloud blog series, we're covering the basics of AWS cloud services for newcomers who are .NET developers. If you love C# but are new to AWS, or to this particular service, this should give you a jumpstart.

In this post we'll introduce the AWS Deployment Tool for .NET and use it to deploy a "Hello, Cloud" .NET program to several different AWS services. We'll do this step-by-step, making no assumptions other than familiarity with C# and Visual Studio. We're using Visual Studio 2022 and .NET 6.

## Our Hello, .NET Deploy Project

We will create a Blazor WebAssembly project and a Web API project. We'll use the AWS .NET deployment tool to deploy the Blazor project to S3 and CloudFront. Then we'll deploy the Web API project, first to AWS Elastic Beanstalk, and afterward to Amazon ECS.

See the blog post for the tutorial to create this project and run it on AWS.

