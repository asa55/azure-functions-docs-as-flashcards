##

All of these services can solve integration problems and automate business processes. They can all define input, actions, conditions, and output. You can run each of them on a schedule or trigger. Each service has unique advantages:

- `_____`
- `_____`
- `_____`
- `_____`

%

- Microsoft Power Automate (was Microsoft Flow)
- Azure Logic Apps
- Azure Functions
- Azure App Service WebJobs

##

Power Automate and Logic Apps are both `_____` integration services that can create workflows. Both services integrate with various SaaS and enterprise applications.

%

Power Automate and Logic Apps are both **designer-first** integration services that can create workflows. Both services integrate with various SaaS and enterprise applications.

##

Power Automate is built on top of `_____`. They share the same workflow designer and the same connectors.

%

Power Automate is built on top of **Logic Apps**. They share the same workflow designer and the same connectors.

##

Power Automate empowers any office worker to perform simple integrations (for example, an approval process on a SharePoint Document Library) without going through developers or

%

IT

##

Logic Apps can also enable advanced integrations (for example, B2B processes) where enterprise-level Azure DevOps and security practices are required. It's typical for a business workflow to grow in complexity over

%

time

##

Power Automate users:

- `_____`
- `_____`
- `_____`

%

- Office workers
- business users
- SharePoint administrators

##

Logic Apps users:

- `_____`
- `_____`

%

- Pro integrators and developers
- IT pros

##

Power Automate scenarios:

- `_____`

%

- Self-service

##

Logic Apps scenarios:

- `_____`

%

- Advanced integrations

##

Power Automate design tool:

- `_____`

%

- In-browser and mobile app (UI only)

##

Logic Apps design tool:

- `_____`
- `_____`
- `_____`

%

- In-browser
- Visual Studio Code
- Visual Studio with code view available

##

Power Automate Application lifecycle management (ALM):

- `_____`

%

- Design and test in non-production environments, promote to production when ready

##

Logic Apps Application lifecycle management (ALM):

- `_____`

%

- Azure DevOps: source control, testing, support, automation, and manageability in Azure Resource Manager

##

Power Automate admin experience:

- `_____`

%

- Manage Power Automate environments and data loss prevention (DLP) policies, track licensing: Admin center

##

Logic Apps admin experience:

- `_____`

%

- Manage resource groups, connections, access management, and logging: Azure portal

##

Power Automate security:

- `_____`

%

- Microsoft 365 security audit logs, DLP, encryption at rest for sensitive data

##

Logic Apps security:

- `_____`

%

- Security assurance of Azure: Azure security, Microsoft Defender for Cloud, audit logs

##

Functions and Logic Apps are Azure services that enable serverless

%

workloads

##

Azure Functions is a serverless compute service, whereas Azure Logic Apps is a serverless

%

workflow integration platform

##

Both Azure Functions and Azure Logic Apps can create complex orchestrations. An orchestration is a collection of functions, or actions in Azure Logic Apps, that you can run to complete a complex

%

task

##

To process a batch of orders, you might execute many instances of a function in parallel, wait for all instances to finish, and then execute a function that computes a result on the aggregate. This is an example of

%

orchestrations

##

For Azure Functions, you develop orchestrations by writing code and using the `_____` Functions extension. For Azure Logic Apps, you create orchestrations by using a `_____` or editing configuration files.

%

For Azure Functions, you develop orchestrations by writing code and using the **Durable** Functions extension. For Azure Logic Apps, you create orchestrations by using a **GUI** or editing configuration files.

##

You can mix and match services when you build an orchestration, such as calling functions from logic app workflows and calling logic app workflows from functions. Choose how to build each orchestration based on the services' capabilities or your

%

personal preference

##

Durable Functions development is code-first, aka

%

imperative

##

Logic Apps development is designer-first, aka

%

declarative

##

Durable Functions connectivity:

- About a dozen built-in `_____` types
- write code for custom `_____`

%

- About a dozen built-in **binding** types
- write code for custom **bindings**

##

Logic Apps connectivity:

- Large collection of `_____`
- Enterprise Integration Pack for `_____` scenarios
- build custom `_____`

%

- Large collection of **connectors**
- Enterprise Integration Pack for **B2B** scenarios
- build custom **connectors**

##

Durable Functions actions:

- Each `_____` is an Azure function
- write code for `_____` functions

%

- Each **activity** is an Azure function
- write code for **activity** functions

##

Logic Apps offer a large collection of ready-made

%

actions

##

Durable Functions monitoring is performed with

%

Azure Application Insights

##

Logic Apps monitoring:

- Azure `_____`
- Azure `_____` logs
- Microsoft `_____` for Cloud

%

- Azure **portal**
- Azure **Monitor** logs
- Microsoft **Defender** for Cloud

##

Durable Functions management can be performed with

- `_____`
- `_____`

%

- REST API
- Visual Studio

##

Logic Apps management can be performed with

- `_____`
- `_____`
- `_____`
- `_____`

%

- Azure portal
- REST API
- PowerShell
- Visual Studio

##

Durable Functions execution context: can run locally or in

%

the cloud

##

Logic Apps execution context: Runs in Azure, locally, or

%

on premises

##

Like Azure Functions, Azure App Service WebJobs with the WebJobs SDK is a code-first `_____` service that is designed for developers. Both are built on Azure App Service and support features such as source control integration, authentication, and monitoring with Application Insights integration.

%

Like Azure Functions, Azure App Service WebJobs with the WebJobs SDK is a code-first **integration** service that is designed for developers. Both are built on Azure App Service and support features such as source control integration, authentication, and monitoring with Application Insights integration.

##

You can use the `_____` feature of App Service to run a script or code in the context of an App Service web app. The `_____` SDK is a framework designed for `_____` that simplifies the code you write to respond to events in Azure services. For example, you might respond to the creation of an image blob in Azure Storage by creating a thumbnail image. The `_____` SDK runs as a .NET console application, which you can deploy to a `_____`.

%

You can use the **WebJobs** feature of App Service to run a script or code in the context of an App Service web app. The **WebJobs** SDK is a framework designed for **WebJobs** that simplifies the code you write to respond to events in Azure services. For example, you might respond to the creation of an image blob in Azure Storage by creating a thumbnail image. The **WebJobs** SDK runs as a .NET console application, which you can deploy to a **WebJob**.

##

`_____` and the `_____` SDK work best together, but you can use `_____` without the `_____` SDK and vice versa. A `_____` can run any program or script that runs in the App Service sandbox. A `_____` SDK console application can run anywhere console applications run, such as on-premises servers.

%

**WebJobs** and the **WebJobs** SDK work best together, but you can use **WebJobs** without the **WebJobs** SDK and vice versa. A **WebJob** can run any program or script that runs in the App Service sandbox. A **WebJobs** SDK console application can run anywhere console applications run, such as on-premises servers.

##

Azure Functions is built on the `_____` SDK, so it shares many of the same event triggers and connections to other Azure services.

%

Azure Functions is built on the **WebJobs** SDK, so it shares many of the same event triggers and connections to other Azure services.

##

Choosing between Azure Functions and WebJobs with WebJobs SDK, for serverless app model with automatic scaling, select

%

Functions

##

Choosing between Azure Functions and WebJobs with WebJobs SDK, for develop and test in browser, select

%

Functions

##

Choosing between Azure Functions and WebJobs with WebJobs SDK, for pay-per-use pricing, select

%

Functions

##

Choosing between Azure Functions and WebJobs with WebJobs SDK, for integration with Logic Apps, select

%

Functions

##

Choosing between Azure Functions and WebJobs with WebJobs SDK, for trigger events including Timer, Azure Storage queues and blobs, Azure Service Bus queues and topics, Azure Cosmos DB, or Azure Event Hubs, select

%

either Azure Functions or WebJobs with WebJobs SDK

##

Choosing between Azure Functions and WebJobs with WebJobs SDK, for trigger events including HTTP/WebHook (GitHub, Slack), or Azure Event Grid, select

%

Functions

##

Choosing between Azure Functions and WebJobs with WebJobs SDK, for trigger events including File System, select

%

WebJobs with WebJobs SDK

##

Choosing between Azure Functions and WebJobs with WebJobs SDK, for C# support, select

%

either Azure Functions or WebJobs with WebJobs SDK

##

Choosing between Azure Functions and WebJobs with WebJobs SDK, for F#, JavaScript, Java, Python, or PowerShell support, select

%

Functions

##

Choosing between Azure Functions and WebJobs with WebJobs SDK, for NPM support, select

%

Functions

##

Choosing between Azure Functions and WebJobs with WebJobs SDK, for NuGet support, select

%

either Azure Functions or WebJobs with WebJobs SDK

##

WebJobs (without the WebJobs SDK) supports languages such as C#, Java, JavaScript, Bash, .cmd, .bat, PowerShell, PHP, TypeScript, Python, and more. A WebJob can run any program or script that can run in the

%

App Service sandbox

##

WebJobs (without the WebJobs SDK) supports NuGet and

%

NPM

##

Azure Functions offers more developer productivity than Azure App Service `_____` does.

%

Azure Functions offers more developer productivity than Azure App Service **WebJobs** does.

##

Azure Functions also offers more options for programming languages, development environments, Azure service integration, and pricing. For most scenarios, it's the best

%

choice

##

Here are two scenarios for which WebJobs may be the best choice:

- `_____`
- `_____`

%

- You need more control over the code that listens for events, the JobHost object. 
- You have an App Service app for which you want to run code snippets, and you want to manage them together in the same Azure DevOps environment.

##

Functions offers a limited number of ways to customize `_____` behavior in the host.json file. Sometimes you need to do things that can't be specified by a string in a JSON file. For example, only the WebJobs SDK lets you configure a custom retry policy for Azure Storage.

%

Functions offers a limited number of ways to customize **JobHost** behavior in the host.json file. Sometimes you need to do things that can't be specified by a string in a JSON file. For example, only the WebJobs SDK lets you configure a custom retry policy for Azure Storage.

##

For scenarios where you want to run code snippets for integrating Azure or third-party services, choose `_____` over WebJobs with the WebJobs SDK.

%

For scenarios where you want to run code snippets for integrating Azure or third-party services, choose **Azure Functions** over WebJobs with the WebJobs SDK.

##

Between Power Automate, Logic Apps, Functions, and WebJobs, you don't have to choose just one of these services. They integrate with each other as well as with

%

external services

##

A Power Automate flow can call an Azure Logic Apps

%

workflow

##

An Azure Logic Apps workflow can `_____` a function in Azure Functions, and vice versa

%

An Azure Logic Apps workflow can **call** a function in Azure Functions, and vice versa

##

Between Power Automate, Logic Apps, and Functions, you can build a component in one service and use that component in the other services. The integration experience between these services continues to improve over

%

time
