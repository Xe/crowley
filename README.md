# crowley

Crowley is an experimental HTTP router for microservices. It has backends connect to the load balancer instead of the load balancer connecting to backends. This model allows networks to be vastly simplified, no longer having to bring in consul or another consensus layer, no more configuration generation or rehashing nginx on each deploy.

## About

Project Stability: Development (don't use this in production at all yet)

This project is a passion project, as such excuse the atypical setup for everything. If you have ideas on how to improve things, please open an issue, comment on existing issues or hit me up in a private message somewhere. I want route to be the easiest possible way to host services of all sizes.
