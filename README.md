# How to deploy a .NET 8 WebAPI in Azure WebApp service

## 1. Create .NET 8 Web API with VSCode

Create a new folder where to place the application 

Open VSCode with the command:

```
code .
```

Create a new .NET 8 WebAPI with this command:

```
dotnet new webapi --framework net8.0
```

![image](https://github.com/luiscoco/Azure_WebApp_Deploy_WebAPIdotNET8/assets/32194879/474c254b-87a3-4a18-954e-01f508363615)

Run the application to verify 

```
dotnet run
```

![image](https://github.com/luiscoco/Azure_WebApp_Deploy_WebAPIdotNET8/assets/32194879/ca096763-ed5c-4446-97ab-7febcf1cc1db)

![image](https://github.com/luiscoco/Azure_WebApp_Deploy_WebAPIdotNET8/assets/32194879/64dd41e1-b2f3-4fc0-9f2f-4e7d7f8bbada)

## 2. Deploy the application to Azure Web App service

In the left menu select Azure extension

![image](https://github.com/luiscoco/Azure_WebApp_Deploy_WebAPIdotNET8/assets/32194879/81c19f70-5e05-4af2-88c9-46f81f72202d)

![image](https://github.com/luiscoco/Azure_WebApp_Deploy_WebAPIdotNET8/assets/32194879/b8335dd1-73c1-4306-bd21-88b10a7cfee1)

Set the .NET 8 Web API name

![image](https://github.com/luiscoco/Azure_WebApp_Deploy_WebAPIdotNET8/assets/32194879/7aa860b4-a31e-4a2b-b8a0-001f124948f3)

![image](https://github.com/luiscoco/Azure_WebApp_Deploy_WebAPIdotNET8/assets/32194879/bd04565f-ad23-49b3-9fb4-ca91dfb5db18)

![image](https://github.com/luiscoco/Azure_WebApp_Deploy_WebAPIdotNET8/assets/32194879/34bd7db7-1038-41c1-8a01-dc7dd6ea7777)

Select the .NET 8 framework

![image](https://github.com/luiscoco/Azure_WebApp_Deploy_WebAPIdotNET8/assets/32194879/c94fff53-3c13-4d3c-beb4-4960779acbd8)

Select the operating system linux

![image](https://github.com/luiscoco/Azure_WebApp_Deploy_WebAPIdotNET8/assets/32194879/9f1b0ab8-5a65-46de-9ac8-394295a4a392)

Select the location **East US**

![image](https://github.com/luiscoco/Azure_WebApp_Deploy_WebAPIdotNET8/assets/32194879/17768750-f27e-49b4-8324-11974f2d7f07)

Create a new Service Plan

![image](https://github.com/luiscoco/Azure_WebApp_Deploy_WebAPIdotNET8/assets/32194879/1b82ad3b-c8da-478a-8e33-a8ab2f3b2443)

Enter the new Service Plan name

![image](https://github.com/luiscoco/Azure_WebApp_Deploy_WebAPIdotNET8/assets/32194879/94ae4dbd-7d32-408a-9798-1b224aca3c22)

Select the App Service plan **Basic (B1)**

![image](https://github.com/luiscoco/Azure_WebApp_Deploy_WebAPIdotNET8/assets/32194879/d3135a2b-b6aa-478f-96bc-d9f4833679f2)

Skip creating a new Application Insights resource

![image](https://github.com/luiscoco/Azure_WebApp_Deploy_WebAPIdotNET8/assets/32194879/a44a6ce6-7416-4edc-8167-77a380ca1e85)

Create a new deployment

![image](https://github.com/luiscoco/Azure_WebApp_Deploy_WebAPIdotNET8/assets/32194879/f8de1fff-15d0-4cb3-989c-6b086a7086b4)

Place the Web API in a folder

![image](https://github.com/luiscoco/Azure_WebApp_Deploy_WebAPIdotNET8/assets/32194879/4d79748a-422e-4e0b-84ae-b42f214e362b)

![image](https://github.com/luiscoco/Azure_WebApp_Deploy_WebAPIdotNET8/assets/32194879/4cfad757-7707-43a3-830d-26a55a73daa7)

![image](https://github.com/luiscoco/Azure_WebApp_Deploy_WebAPIdotNET8/assets/32194879/c8b90445-7b5b-4f8e-ae85-1955b55bf82c)

![image](https://github.com/luiscoco/Azure_WebApp_Deploy_WebAPIdotNET8/assets/32194879/b5e16994-466a-4443-b483-9ee4e7438fde)

![image](https://github.com/luiscoco/Azure_WebApp_Deploy_WebAPIdotNET8/assets/32194879/f50c83a4-1aa7-498f-80f0-eda0692c6372)

![image](https://github.com/luiscoco/Azure_WebApp_Deploy_WebAPIdotNET8/assets/32194879/5dd7dede-fd0a-47f2-bf50-ce8d5bc55f81)
