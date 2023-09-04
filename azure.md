Storage

1. Azure File
   - Description
      As far as I’m concerned, the Azure file storage service, compared to the Blob, stresses file sharing. The unique point is that you can access the files from anywhere in the world using a URL that includes a shared access signature (SAS) token.
   - Python interaction
  Similar to Blob, the interaction is realized via SDK through the installation of the storage client library.

  
2. Blob
   - Description
   Blob Storage is optimized for storing massive amounts of unstructured data, such as text or binary data. The ideal usage that I can relate to so far includes storing data for backup, restore, and archiving, as well as streaming video and audio. Users can access objects via HTTP or HTTPS.
   - Python interaction
   The Azure Blob Storage blobs and containers can be managed using Python through an interactive console app, or, as I interpreted it, a CLI. Installation of storage client libraries and identity packages is needed. I vaguely reckon that the interaction is realized via SDK. I’m not sure about the difference between SDK and libraries.

Compute

1. Azure Functions
   - Description
     Azure Functions provides all the continually updated infrastructure and resources needed to run applications. Users focus on the code that matters most, in the most productive language, and Functions handle the rest. Functions provides serverless computing for Azure.  Functions can be used to build web APIs, respond to database changes, process IoT streams, manage message queues, and more.
   - Python interaction
Functions in Azure with Python can be created using VS Code. Python extensions and Azure functions extensions are needed.

2. Azure App Service
   - Description
     Azure App Service is a fully managed web hosting service that supports Python apps hosted in a Linux server environment. It is used to deploy and develop enterprise-ready web and mobile applications.
   - Python interaction
     A python web app deployment can be fulfilled via Django or Flask - web app frameworks in Python.


Database
1. Azure SQL Database
   - Description
     Build apps that scale with a fully managed and intelligent SQL database built for the cloud. Grow applications with near-limitless storage capacity and responsive serverless compute, backed by AI-based advanced security.
   - Python interaction
       Work with data stored in Azure SQL Database from Python with the pyodbc ODBC database driver. View our quickstart on connecting to an Azure SQL Database and using Transact-SQL statements to query data and getting started sample with pyodbc.

2. Azure Cosmos DB
   - Description
     Distributed NoSQL and relational databases for modern app development.
   - Python interaction
     Azure Cosmos DB libraries for Python


Reference

https://learn.microsoft.com/en-us/azure/storage/common/storage-introduction
https://learn.microsoft.com/en-us/azure/storage/blobs/storage-quickstart-blobs-python?tabs=managed-identity%2Croles-azure-portal%2Csign-in-azure-cli
https://learn.microsoft.com/en-us/azure/storage/files/storage-python-how-to-use-file-storage?tabs=python
https://azure.microsoft.com/en-us/products/app-service
https://learn.microsoft.com/en-us/python/api/overview/azure/sql?view=azure-python

