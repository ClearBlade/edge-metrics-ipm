
# ipm package: edge-metrics-ipm

## Overview



This IPM includes the **edge-metrics** library for capturing CPU, Disk, Memory and Network / Data usage from. It includes an example microservice that shows how to call the functions in the library.

[Browse ipm Packages](https://ipm.clearblade.com)

## Setup

Install the IPM in a ClearBlade environment (e.g. platform.clearblade.com). If you are unfamiliar with installing an IPM the following steps will help.
1. Login to the environment using a valid Developer account (you may need to register in advance).
2. Click **Add System >> Advanced**, paste the link to this repo (https://github.com/ClearBlade/edge-metrics-ipm) in the input provided and click **Fetch**.

## Usage

1. Spin up an **edge** in your system. If you are unfamiliar with spinning up an edge the following links can help:
https://docs.clearblade.com/v/4/edge/
https://docs.clearblade.com/v/4/edge/tutorial/

2. Create a Deployment to deploy the library and microservice to your edge. If you're unfamiliar with Deployments the following links can help:
https://docs.clearblade.com/v/4/deployment/
https://docs.clearblade.com/v/4/deployment/tutorial/

3. Login to the edge and run the example microservice - **testEdgeMetrics**. Notice the service logs disk, cpu, memory, and data (network) usage by calling the appropriate functions in the **edge_metrics** library.
