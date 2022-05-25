# Simple authenticated proxy

Remote proxy is a simple but useful tool to protect your API servers, it has been created for different blockchain nodes and has been tested for Ethereum, Avalanche and Algorand but it works for any API endpoint that you wish to hide its IP and location from the public. 

You can set an anauthentication token to make your API private and the proxy also comes with a rate limiter to prevent Ddos attacks and abuse from users. 

## Install
1. `cp .env-default .env`
2. Modify .env file according to proxy requirements, `REDIRECT_*` variables are for where to redirect the incoming request
3. `docker-compose up -d`
