# axonius-for-splunk

Testing out some stuff for the Axonius Technical Add-On.
This should serve as a boilerplate for local development.


## What you need to get started

* Splunk License - drop it into the splunk-licenses directory as `splunk.lic`
* Splunkbase account  - The SVC Axonius account can work. 
You need the following environment variables: SPLUNKBASE_USERNAME & SPLUNKBASE_PASSWORD 
* Put those environment variables in an `.env` file
* Docker is a must as well (currently using docker-compose)

_local devlopment_

`docker-compose --env-file .env up  -d`

The docker container should contain the Splunk Add-On Builder if configured correctly.

## Now how is the app built?
