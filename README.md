# My First NSwag Application

+ NSwag.AspNetCore
+ NSwag.MSBuild

This is a simple application to demonstrate the use of NSwag to generate a swagger client for a Web API with a .NET 8 backend. 

Each branch of this repository will demonstrate a different aspect of the NSwag tooling built upon the base simple .NET 8 application. A detailed list of each branch and its use case will be provided below.

Along with it the link to the medium article explain the use case of each branch will be provided.

1. **main**: A default .NET 8 web application to demonstrate simple NSwag configuration/setup.
2. **customizingnswagdocumentone**: Modified Program.cs with code to customize Open Api document name and title.
2. **customizingnswagdocumentone**: Modified Program.cs with code to customize Swagger Ui hosting path as well as swagger json hosting Uri.
4. **nswagmsbuild1**: Install MSBuild package to .Net 8 application and create swagger.json during post build process.
5. **nswagtypemapper**: Understand Type mapper implementation with a well know long integer rounding off issues.

## Understand & Setup .NET 8 application with NSwag together

https://medium.com/@vamsidogiparthi/understand-setup-net-8-application-with-nswag-together-4aaa4d764c65

## Learn and Understand NSwag Document Generation — Simple use case

https://medium.com/@vamsidogiparthi/learn-and-understand-nswag-document-generation-simple-use-case-4b5099644208

## Understanding Type Mapper from NSwag with .NET 8

https://medium.com/@vamsidogiparthi/understanding-type-mapper-from-nswag-with-net-8-418d1a034477

https://github.com/vamsidogiparthi/MyFirstNSwagApplication/tree/typemapperexample

## Learn and Understand How to generate Swagger.Json via MSBuild and .NET 8 with simple start up

https://medium.com/@vamsidogiparthi/learn-and-understand-how-to-generate-swagger-json-via-msbuild-and-net-8-with-simple-start-up-d7ad6c3cf74b

https://github.com/vamsidogiparthi/MyFirstNSwagApplication/tree/nswagmsbuild1

## Customize Open Api document name and title + Customize Swagger UI hosting path as well as swagger json hosting Uri

https://github.com/vamsidogiparthi/MyFirstNSwagApplication/tree/customizingnswagdocumentone

## Customize Open Api document name and title + Customize Swagger UI hosting path as well as swagger json hosting Uri

https://github.com/vamsidogiparthi/MyFirstNSwagApplication/tree/customuriforswagger

## Install MSBuild package to .Net 8 application and create swagger.json during post build process.

https://github.com/vamsidogiparthi/MyFirstNSwagApplication/tree/nswagmsbuild1
