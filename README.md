# **Setting up a local version of the application**

## **1. Create environment variables**

First create a .env file to host the necessary environmental variable in the **root** of the project directory.

**Required variables**

| Name | Details                          |
| ---- | -------------------------------- |
| PORT | Port number for server to run on |

Next create another .env file in the **root** of the "client" directory.

**Required variables**

| Name              | Details                  |
| ----------------- | ------------------------ |
| REACT_APP_API_KEY | Foursquare PlacesAPI key |

The Foursquare PlacesAPI key can be obtained by creating a Foursqure account.

For more details, visit: https://developer.foursquare.com/docs/places-api-overview

## **2. Building the application**

From the root of the project folder, navigate to the client folder.

<code>cd client</code>

Run the build command.

<code>npm run build </code>

## **3. Starting the application**

Navigate back to the root directory.

<code>cd.. </code>

Start the server.

<code>npm start</code>

Open the web browser and visit **localhost:PORT**.

## **4. Application Demo**

![Application Demo](./media/Dinear-demo.gif)
