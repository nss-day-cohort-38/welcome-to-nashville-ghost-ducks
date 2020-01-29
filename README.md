BASIC README FRAMEWORK

1. Install [http-server](https://www.npmjs.com/package/http-server)
2. clone/download
3. create api file 'apikeys.js'
    -find api keys for zomato & ticketmaster
    -define zomato key as 'restaurantsAPIKey'
    -define ticketmaster key as 'concertKey'
4. cd to source directory
5. hs -o
6. explain functionality
    -parks functionality
    -art functionality
    -restaurant functionality
    -concert functionality

*****
TICKETMASTER INSTRUCTIONS

Make sure to get a ticketmaster api key for this program to work properly.
You can get this api key by [registering with Ticketmaster] (https://developer-acct.ticketmaster.com/user/register)
Once you have it copy your key in your apiKeys.js file as: const concertKey = "YOUR_KEY_HERE"
Access Zomato API to use restaurants search feature
*****
ZOMATO INSTRUCTIONS

1. Visit developers.zomato.com/api to request and obtain an API key
2. create "apiKeys.js" inside scripts folder. 
3. copy the API key into apiKeys.js as: const restaurantsAPIKey = "YOUR_KEY_HERE"
