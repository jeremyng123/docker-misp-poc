# POC testing
For those who are here for project POC testing, please read this README as well.

# Getting Started
First of all, follow all the steps detailed in README.md (as written by ostefano's [repo](https://github.com/ostefano/docker-misp)) up
until we run the docker images.

Before you run the image as a container (i.e., `docker compose up`), make sure to set up your environment variables first.


For the purpose of this POC, I have created 3 misp instances from ports 6000, 6001 and 6002 for `misp0`, `misp1`, `misp2` respectively.
The environment variable has already been given `"HOSTNAME=${HOSTNAME}:6000|6001|6002"`. It is hence the developer's duty to update the hostname
in the `.env` file (defaults to `https://localhost`. Notice the protocol is included in the hostname).

With that, you are ready to start the poc

# Motivation
Why are we doing this?

1. Trying a poc where our local MISP is connected to remote MISPs.
2. Testing different access controls and confirming data controls assessments



# Architecture
TODO