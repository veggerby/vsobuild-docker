# vsobuild-docker

Docker container for VSTS Node.js build agent

Docker Hub Repository: [veggerby/vsoagent](https://hub.docker.com/r/veggerby/vsoagent/)

Based on [renevanosnabrugge/vsobuild-docker](https://github.com/renevanosnabrugge/vsobuild-docker)

Run with:

    docker run -it --name vsoagent -e VSO_CONFIG_USERNAME=[username] -e VSO_CONFIG_PASSWORD=[password] -e VSO_CONFIG_URL=https://[vsts-host].visualstudio.com/ veggerby/vsoagent
