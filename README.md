# Serverless Functions
## Database
![cosmosdb-overview](./images/cosmosdb-overview.png)

![cosmosdb-advertisements-sample](./images/cosmosdb-advertisements-sample.png)

![cosmosdb-posts-sample](./images/cosmosdb-posts-sample.png)

## Triggers in Azure
![functionapp-overview](./images/functionapp-overview.png)
![functionapp-triggers](./images/functionapp-triggers.png)
![functionapp-timertrigger](./images/functionapp-timertrigger.png)


Functions in func-toast-neighborly-api:

    createAdvertisement - [httpTrigger]
        Invoke url: https://func-toast-neighborly-api.azurewebsites.net/api/createadvertisement

    createPost - [httpTrigger]
        Invoke url: https://func-toast-neighborly-api.azurewebsites.net/api/createpost

    deleteAdvertisement - [httpTrigger]
        Invoke url: https://func-toast-neighborly-api.azurewebsites.net/api/deleteadvertisement?code=d4VABNMIzhiPPgHECrioIqdefNNUiTK6Fac7onx5Wbuysmao0DUafw==

    deletePost - [httpTrigger]
        Invoke url: https://func-toast-neighborly-api.azurewebsites.net/api/deletepost?code=KfxwLgXYufFnau7XXojVD4oerY/zqdRo9VtC1nrE7BU32OAuBy9D5A==

    eventHubTrigger - [eventGridTrigger]

    getAdvertisement - [httpTrigger]
        Invoke url: https://func-toast-neighborly-api.azurewebsites.net/api/getadvertisement

    getAdvertisements - [httpTrigger]
        Invoke url: https://func-toast-neighborly-api.azurewebsites.net/api/getadvertisements

    getPost - [httpTrigger]
        Invoke url: https://func-toast-neighborly-api.azurewebsites.net/api/getpost

    getPosts - [httpTrigger]
        Invoke url: https://func-toast-neighborly-api.azurewebsites.net/api/getposts

    timerTrigger - [timerTrigger]

    updateAdvertisement - [httpTrigger]
        Invoke url: https://func-toast-neighborly-api.azurewebsites.net/api/updateadvertisement

    updatePost - [httpTrigger]
        Invoke url: https://func-toast-neighborly-api.azurewebsites.net/api/updatepost


## Triggers Connect to Database
![functionapp-Postman-getAdvertisements](./images/functionapp-Postman-getAdvertisements.png)
![functionapp-Postman-getPosts](./images/functionapp-Postman-getPosts.png)

## Flask Front End: Localhost
![flask-localhost](./images/flask-localhost.png)

# Logic Apps & Event Hubs
## Logic App
![logicapp-history](./images/logicapp-history.png)
![logicapp-email](./images/logicapp-email.png)

## Event Hub
![eventgrid-overview](./images/eventgrid-overview.png)
![eventgrid-log](./images/eventgrid-log.png)
![eventgrid-logic app](./images/eventgrid-logicapp.png)

# Deploying Your Application
![resource-group](./images/resource-group.png)
## App Service Deployment
Live URL: https://app-toast-neighborly.azurewebsites.net/

![flask-app-home](./images/flask-app-home.png)
![flask-app-home2](./images/flask-app-home2.png)
![flask-app-add-ad](./images/flask-app-add-ad.png)
![flask-app-add-get](./images/flask-app-add-get.png)
![flask-app-add-delete](./images/flask-app-ad-delete.png)

## Dockerfile
![docker-local-images-console](./images/docker-local-images-console.png)
![docker-local-container](./images/docker-local-container.png)
![docker-azure-container](./images/docker-azure-container.png)

## Kubernetes
![kubernetes-nodes](./images/kubernetes-nodes.png)
![kubernetes-config](./images/kubernetes-config.png)
![kubernetes-service](./images/kubernetes-service.png)
![kubernetes-web](./images/kubernetes-web.png)