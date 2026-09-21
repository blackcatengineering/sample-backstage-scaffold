# OpenStack Magnum 3-Tier App Documentation

Welcome to the internal documentation for your newly scaffolded 3-tier application template.

## Architecture Overview
This blueprint establishes three core operational layers inside an OpenStack Magnum Kubernetes environment:
* **Frontend Tier:** Handles routing via Ingress or direct Octavia LoadBalancers.
* **Backend Tier:** Formulates logic pathways and connects to persistent data.
* **Database Tier:** Backed securely by OpenStack Cinder Block Storage via a `standard` StorageClass.

## Getting Started
To get this up and running, trigger the Backstage Scaffolder execution pipeline.
