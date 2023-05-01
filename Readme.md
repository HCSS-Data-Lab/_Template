# About <solution name>
[![Publish HCSS <solution name> docker image](https://github.com/HCSS-Data-Lab/<gitname>/actions/workflows/action.yml/badge.svg?branch=<main>)](https://github.com/HCSS-Data-Lab/<gitname>/actions/workflows/action.yml)

## Frameworks used
- <Framework 1>

# Docker image details
## <solution name>
Base image:
Exposed ports:
Additional installed resources:
- Troubleshooting:
- Python libraries:

# Deployment
## General
Service: <solution name>
Data Path: /home/worker/hcss/<solution name>/
Access URL: <solution name>.app.hcss.nl

## Attached Networks
- traefik-public - access to reverse proxy

## Attached volumes
<solution name>data: used for persistency

## Environment variables
Describe what environment variables need to be configured for the solution to run.

# Authentication
Is any authentication solution configured?
