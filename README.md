# PROCHECK API Machine to Machine Communication Notebook

This Code is meant to show how to communicate with PROCHECK using your own Backend Software

_Note:_ it's important to receive from Prometeon Administrators these Credentials in order to Proceed:

```
OAUTH_DOMAIN
OAUTH_CLIENT_ID
OAUTH_SECRET
PROCHECK_API_URL
```

All code is Build with Jupyter, the easiest way to test it is using Docker, following these steps:

1. Create a .env file in the root folder and fill it with the actual credentials that Prometeon provided you.
2. `docker-compose up`
3. Follow the url propted by jupyter on your browser (i.e. `http://127.0.0.1:8888/?token=<token>`)
4. Click on the `OAuthM2M.ipynb` Notebook and click on run all cells

_By Default PROCHECK_API_URL will point to Production environment change that URL in case of need_

PROCHECK API DOCS can be found here: https://procheck.prometeon.com/api_documentation
