# MongoDB

MongoDB is a free and open-source cross-platform document-oriented database program. Classified as a NoSQL database program, MongoDB uses JSON-like documents with schemata.

In this project I have deployed mongodb on Napptive catalog. I have added user interface so that any one can perform CRUD operations in user friendly manner.

## How to Deploy MongoDB on NAPPTIVE PLAYGROUND
1. Before Deploying the application on NAPPTIVE first we need to create an OAM file(Open Application model) for doing this we need to create a YAML file in which we can add the component and properties required to migrate the application in OAM.
1. A Component represents a single microservice from the Application. To define it, select the type of component that adapts best to the use case, and define its properties. here I have choose webservice(Describes long-running, scalable, containerized services that have a stable network endpoint to receive external network traffic from customers)
1. A Trait represents an extension for an application component. This facilitates reusing components in different situations, and simplifies their packaging as the developer does not need to add any extra information for its deployment. 
1. After you've completed all of this, upload the yaml file to the NAPPTIVE platform and click the Deploy button.
1. After deployment click on the endpoint link you will see this interface to access Nextcloud
1. Finally, you can see on the screen that your application is running.<br>
   here is the [link](mongo-visualizer-cgs39hbh51taq9hpjmr0.apps.hackathon.napptive.dev)
![image](https://user-images.githubusercontent.com/95087459/232234292-9674cd38-d451-4af7-9007-77f3052080f3.png)

## Uploading your application to the catalog
To upload an application to the catalog, you will need to prepare at least three files:

1. The raw YAML files that define the application. In this example, the mongo.app.yaml file you created in the previous steps.
1. A README.md file with the content that will be shown when navigating the catalog to describe what the application does and how to use it. A detailed README will help other team members to use the application.
1. A metadata file that defines what the application is so that it can be searched in the catalog.
