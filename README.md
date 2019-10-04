This app is based on [GitHub App](https://developer.github.com/apps/about-apps/) as a foundation.

The GitHub App listens to repository events, and when a new repository is created it adds pretections to the master branch.

You can read more about GitHub Apps here: https://developer.github.com/apps/

*__NOTE:__ If you are interested in a Java version, take a look at a basic WebHook implementation written in Java that listens to WebHook notifications https://github.com/regpaco-org/githook*

## Pre-Requisites

To run this locally, configure your env by following the "[Setting up your development environment](https://developer.github.com/apps/quickstart-guides/setting-up-your-development-environment/)" quickstart guide on developer.github.com.


## Install

To run the code, make sure you have [Bundler](http://gembundler.com/) installed; then enter `bundle install` on the command line.

## Set environment variables

1. Create a copy of the `.env-example` file called `.env`.
2. Add your GitHub App's private key, app ID, and webhook secret to the `.env` file.

## Run the server

1. Run `ruby template_server.rb` on the command line.
1. View the default Sinatra app at `localhost:3000`.

## Useful Links
http://octokit.github.io/octokit.rb/Octokit.html
https://developer.github.com/apps/quickstart-guides/using-the-github-api-in-your-app/
https://developer.github.com/apps/about-apps/
