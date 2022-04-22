# Runner-Elasticity-With-Cloud
[WIP] - Orb to come soon
## Installation & Usage
This project contains sample configuration using CircleCI's continuation API, along with piepline parameters to 
delegate whether a workflow should run using a self-hosted runner, or CircleCI's cloud executors. 

## Required Project Settings:
RUNNER_API_TOKEN and RESOURCE_CLASS must be defined within your project's settings in CircleCI. Please specify runner_threshold
as a pipeline parameter in the setup configuration.

### About
This is an ideal solution for those that are interested in using a self-hosted runner as the primary executor for
CircleCI workflows, with the option to utilize elasticity of CircleCI's cloud-hosted resources when the runner queue
depth exceeds a set threshold.