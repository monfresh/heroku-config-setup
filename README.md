Automate the setup of a Heroku app
===================================

While writing a [tutorial](https://github.com/codeforamerica/ohana-api/wiki/How-to-deploy-the-Ohana-API-to-your-Heroku-account) for deploying the open-source [Ohana API](https://github.com/codeforamerica/ohana-api) to Heroku, I realized that there were many commands to run in order to set the required environment variables, add-ons, and run the setup scripts.

Once a system has been configured to push to Heroku, it should be able to run all the commands without user intervention, so I wrote this script that runs all the necessary commands. It's specific to the Ohana API, but it could serve as a starting point for your app.
