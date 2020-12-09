Hi @GithubUsername

For .NET, the development focus shifted to the next generation of Azure SDKs which follows the [new SDK guideline](https://azure.github.io/azure-sdk/general_introduction.html) and introduces a set of important new featuers. Those new packages are currently in preview state and we are actively working on making it production ready. You can visit [this link here](https://azure.github.io/azure-sdk/releases/latest/mgmt/dotnet.html) to see the latest .NET packages: 

We have also published a few blog posts on why we are doing this:
https://devblogs.microsoft.com/azure-sdk/october-2020-management-ga/
https://devblogs.microsoft.com/azure-sdk/introducing-new-previews-for-azure-management-libraries/

With this background, .NET Fluent is currently in a low maintenance mode, and we mostly do security and bug fixes. It is subject to deprecation in the future when the new set of .NET packages become Generally Available (GA). Please let us know if there are further questions, thanks!
