# MongoDB

- Create a MongoDB account
- Get started
- Create a new cluster
- Network access
- Database access
- Connect to your cluster in MongoDB
    - Access the connection string

**Updated as of July 2022*

## Create a MongoDB account

Visit the [MongoDB website](https://account.mongodb.com/account/login?_ga=2.181341280.658035587.1656842008-1021176239.1655982411) to create an account, or just to sign in with your existing Google or Github accounts.

<img width="1439" alt="create_account" src="https://user-images.githubusercontent.com/35587864/177120577-b81b7605-c4d7-4150-9463-1924f5577093.png">

## Get started

For basic configuration options, just choose the `Free - Shared` option and click on `Create`.

<img width="1440" alt="getting_started" src="https://user-images.githubusercontent.com/35587864/177120643-23594523-2f45-459e-ab7a-17a29be7d048.png">

## Create a new cluster

Select your region on `Cloud Provider & Region`, or pick another region closest to your region - if your region is not available. Then click on the `Create Cluster`.

<img width="1440" alt="create_cluster" src="https://user-images.githubusercontent.com/35587864/177120698-26bc0786-529e-4ed3-b206-7bdb77578988.png">

## Network access

Click on `Network Access` on the left panel, then click on `Add IP Address` in the centre.

![network_access_1-01](https://user-images.githubusercontent.com/35587864/177120786-a9ea3cbc-503f-4497-b5b3-f50915dcf4fc.png)

Click on `ADD CURRENT IP ADDRESS` so that your current IP address will be automatically generated on `Access List Entry`. Then click `confirm`.

![network_access_2-01](https://user-images.githubusercontent.com/35587864/177120837-134d9307-e95d-4aa1-8496-9b08c6aacd09.png)

Your `Network Access` panel should then look like the following:

![network_access_3](https://user-images.githubusercontent.com/35587864/177120870-9c4c0350-f6c4-4c32-8ec8-733cd86e0a40.png)

## Database access

Click on `Database Access` on the left panel, then click on `Add New Database User` in the centre.

![database_access_1](https://user-images.githubusercontent.com/35587864/177120912-e4ab3f43-8087-4932-afc0-43c622493996.png)

Enter your username and password, then click on `Add User`.

![database_access_2](https://user-images.githubusercontent.com/35587864/177120930-682affe6-7ecb-49db-8354-8439841918be.png)

Your `Database Access` panel should then look like the following:

![database_access_3](https://user-images.githubusercontent.com/35587864/177120974-4139d1f0-63b3-4635-b4b9-ca9521b23442.png)

## Connect to your cluster in MongoDB

Click on `Database` on the left panel, then click on `Connect`.

![connect_cluster](https://user-images.githubusercontent.com/35587864/177121043-7635e9a4-5608-42f7-bef1-70a9597ec2f7.png)

### Access the connection string

Click on `Connect your application` then `Close`.

![connect_cluster_2](https://user-images.githubusercontent.com/35587864/177121075-75838df9-0aa7-4eb3-af69-38f846b468e7.png)

Copy the connection string and paste it onto the `.env` file in your local application. Change the `<password>` part with the password you set up on the `Database Access` panel in MongoDB.

![connect_cluster_3](https://user-images.githubusercontent.com/35587864/177121099-a9e4903e-ea03-4e5e-88f3-7e8e0979609a.png)
