# Getting Started
We are going to download, configure and host a template locally.

## Initialize a new repo
Before you proceed ensure you have the following keys:

* Shopify Admin API Key
* Shopify Admin Key Password
* Shopify storefront access key
* Shopify store name
  
```bash
wipaytemplate init 
```

Follow the prompt and insert the keys above



## Navigate to repo
A folder would have been created using your store name. 
```bash
cd [storename] && code .

#replace [storename] with your actual storename
```
## Install Project Dependencies
```bash
npm install
```

## Start Development Server
We will use gatsby to start a local server (a server on your computer not published to the internet) allowing you to view and intereact with your new webiste. In your project folder run the following command
```bash
gatsby develop
```

## Viewing your website
Open your favorite browser and enter the following address: `http://localhost:8000`

Congrats you have just downloaded and installed your first wipay template.

For as long as your development server running you can visit your site at `http://localhost:8000` To stop th server, go back to your terminal and press CMD+C. To run your server again type `gatsby develop` and hit enter.

## What's Next
Head over to the deployment section to learn how to put your website on the internet for everyone to see. Check out the customization tab for tips on editing look and feel of the template.