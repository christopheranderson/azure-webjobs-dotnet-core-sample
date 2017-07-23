# Azure WebJobs dotnet core 2.0 sample

This is a simple sample on how to use the Azure WebJobs SDK in dotnet core 2.0 apps

![WebJobs running on a mac via dotnet core](https://user-images.githubusercontent.com/2252976/28497154-50ca19c0-6f35-11e7-9ff1-076332c7c30d.png)

## Getting started

To get started you need to add the storage connection string to the appsettings.json file, then run the below commands.

```bash
git clone https://github.com/christopheranderson/azure-webjobs-dotnet-core-sample.git
dotnet restore
dotnet run
```

You need dotnet core 2.0 preview installed for this to work. You can download it [here](https://www.microsoft.com/net/download/core).

## appsettings.json

Instead of an `App.config`, you now use an `appsettings.json` file. You need to have a key for `AzureWebJobsStorage` and `AzureWebJobsDashboard`. 

## LICENSE

[MIT](LICENSE)