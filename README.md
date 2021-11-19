# Blob sample with Javascript

Access a blob behind a firewall using JavaScript.

# Links

* [Azure Storage samples using v12 JavaScript client libraries](https://docs.microsoft.com/en-us/azure/storage/common/storage-samples-javascript)

# Sample using an SAS Token

Based on:
https://github.com/Azure/azure-sdk-for-js/blob/master/sdk/storage/storage-blob/samples/javascript/withConnString.js#L14

We also use:
https://docs.microsoft.com/en-us/azure/storage/blobs/storage-quickstart-blobs-nodejs

# Requiriments

* Git.
* An Azure account.
* A [Storega account](https://docs.microsoft.com/en-us/azure/storage/common/storage-account-create?tabs=azure-portal) witout Hierarchical Namespace Enabled
* Visual Studio Code or any other code editor compatible with Javascript.
* [dotenv](https://robertcooper.me/post/front-end-javascript-environment-variables) to setup the environment variables.
* Install node and module ``@azure/storage-blob``

# Run code

1. create an .env file with the Storage string. Sample: ``STORAGE_CONNECTION_STRING=DefaultEndpointsProtocol=https;AccountName=12blobwithjavascript;AccountKey=XXXX;EndpointSuffix=core.windows.net``
2. Open VS Code’s terminal by clicking Terminal, type node file_name.js where file_name.js is the name of your JavaScript file.
