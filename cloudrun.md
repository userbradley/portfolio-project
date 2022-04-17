# Assignment 3 - Publish it to the web

Woo! Now we have a docker container, we need to actually find a way to send a URL to your nan, so she doesn't have to learn docker.


## What you will achieve here

This section will be quite long, so you'll need to set aside a few hours for this.

By the end of this assignment, you will have a URL on **google cloud, cloud run** (big hint here) that people can navigate to



# Let's start

Like mentioned, you need to publish your site to the world, so create a free [google cloud account](https://cloud.google.com)

## Grading

* Docker container is on gcr.io
* Cloudrun application is created
* Site loads straight from default URL

## Extra points

* Assign a custom URL (You may need to buy a domain, if you don't have one already)

## Technology to use

* Google cloud
* Cloud Run
* [Optional] `gcloud` cli


## What your deployment needs to include

* Autoscaling based on load
* Always have one instance active
* Make it as cheap as possible
* Demonstrate autoscaling (Use a load tester like [locust](https://locust.io)

### Notes from the author

You may need to re-tag your instance and push it to gcr.io, just a hint ;)
