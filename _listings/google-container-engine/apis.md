---
name: Google Container Engine
x-slug: google-container-engine
description: Google Container Engine is a powerful cluster manager and orchestration
  system for running your Docker containers. Container Engine schedules your containers
  into the cluster and manages them automatically based on requirements you define
  (such as CPU and memory). Its built on the open source Kubernetes system, giving
  you the flexibility to take advantage of on-premises, hybrid, or public cloud infrastructure.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/docker-container.png
x-kinRank: "9"
x-alexaRank: "0"
tags: Google Container Engine
created: "2018-08-30"
modified: "2018-08-30"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-container-engine/master/_listings/google-container-engine/apis.md
specificationVersion: "0.14"
apis:
- name: Google Container Engine - Get Clusters
  x-api-slug: v1projectsprojectidzoneszoneclusters-get
  description: Lists all clusters owned by a project in either the specified zone
    or all zones.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/docker-container.png
  humanURL: https://cloud.google.com/container-engine/
  baseURL: ://container.googleapis.com//
  tags: Containers, Google APIs, Stack Network, API Service Provider, API Provider,
    Deployments, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-container-engine/master/_listings/google-container-engine/v1projectsprojectidzoneszoneclusters-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-container-engine/master/_listings/google-container-engine/v1projectsprojectidzoneszoneclusters-get-openapi.md
- name: Google Container Engine - Create Cluster
  x-api-slug: v1projectsprojectidzoneszoneclusters-post
  description: Creates a cluster, consisting of the specified number and type of Google
    Compute Engine instances. By default, the cluster is created in the project's
    [default network](/compute/docs/networks-and-firewalls#networks). One firewall
    is added for the cluster. After cluster creation, the cluster creates routes for
    each node to allow the containers on that node to communicate with all other instances
    in the cluster. Finally, an entry is added to the project's global metadata indicating
    which CIDR range is being used by the cluster.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/docker-container.png
  humanURL: https://cloud.google.com/container-engine/
  baseURL: ://container.googleapis.com//
  tags: Containers, Google APIs, Stack Network, API Service Provider, API Provider,
    Deployments, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-container-engine/master/_listings/google-container-engine/v1projectsprojectidzoneszoneclusters-post-openapi.md
- name: Google Container Engine - Delete Cluster
  x-api-slug: v1projectsprojectidzoneszoneclustersclusterid-delete
  description: Deletes the cluster, including the Kubernetes endpoint and all worker
    nodes. Firewalls and routes that were configured during cluster creation are also
    deleted. Other Google Compute Engine resources that might be in use by the cluster
    (e.g. load balancer resources) will not be deleted if they weren't present at
    the initial create time.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/docker-container.png
  humanURL: https://cloud.google.com/container-engine/
  baseURL: ://container.googleapis.com//
  tags: Containers, Google APIs, Stack Network, API Service Provider, API Provider,
    Deployments, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-container-engine/master/_listings/google-container-engine/v1projectsprojectidzoneszoneclustersclusterid-delete-openapi.md
- name: Google Container Engine - Get Cluster
  x-api-slug: v1projectsprojectidzoneszoneclustersclusterid-get
  description: Gets the details of a specific cluster.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/docker-container.png
  humanURL: https://cloud.google.com/container-engine/
  baseURL: ://container.googleapis.com//
  tags: Containers, Google APIs, Stack Network, API Service Provider, API Provider,
    Deployments, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-container-engine/master/_listings/google-container-engine/v1projectsprojectidzoneszoneclustersclusterid-get-openapi.md
- name: Google Container Engine - Update Cluster
  x-api-slug: v1projectsprojectidzoneszoneclustersclusterid-put
  description: Updates the settings of a specific cluster.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/docker-container.png
  humanURL: https://cloud.google.com/container-engine/
  baseURL: ://container.googleapis.com//
  tags: Containers, Google APIs, Stack Network, API Service Provider, API Provider,
    Deployments, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-container-engine/master/_listings/google-container-engine/v1projectsprojectidzoneszoneclustersclusterid-put-openapi.md
- name: Google Container Engine - Get Cluster Node Pools
  x-api-slug: v1projectsprojectidzoneszoneclustersclusteridnodepools-get
  description: Lists the node pools for a cluster.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/docker-container.png
  humanURL: https://cloud.google.com/container-engine/
  baseURL: ://container.googleapis.com//
  tags: Containers, Google APIs, Stack Network, API Service Provider, API Provider,
    Deployments, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-container-engine/master/_listings/google-container-engine/v1projectsprojectidzoneszoneclustersclusteridnodepools-get-openapi.md
- name: Google Container Engine - Create Cluster Node Pool
  x-api-slug: v1projectsprojectidzoneszoneclustersclusteridnodepools-post
  description: Creates a node pool for a cluster.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/docker-container.png
  humanURL: https://cloud.google.com/container-engine/
  baseURL: ://container.googleapis.com//
  tags: Containers, Google APIs, Stack Network, API Service Provider, API Provider,
    Deployments, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-container-engine/master/_listings/google-container-engine/v1projectsprojectidzoneszoneclustersclusteridnodepools-post-openapi.md
- name: Google Container Engine - Delete Cluster Node Pool
  x-api-slug: v1projectsprojectidzoneszoneclustersclusteridnodepoolsnodepoolid-delete
  description: Deletes a node pool from a cluster.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/docker-container.png
  humanURL: https://cloud.google.com/container-engine/
  baseURL: ://container.googleapis.com//
  tags: Containers, Google APIs, Stack Network, API Service Provider, API Provider,
    Deployments, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-container-engine/master/_listings/google-container-engine/v1projectsprojectidzoneszoneclustersclusteridnodepoolsnodepoolid-delete-openapi.md
- name: Google Container Engine - Get Cluster Node Pool
  x-api-slug: v1projectsprojectidzoneszoneclustersclusteridnodepoolsnodepoolid-get
  description: Retrieves the node pool requested.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/docker-container.png
  humanURL: https://cloud.google.com/container-engine/
  baseURL: ://container.googleapis.com//
  tags: Containers, Google APIs, Stack Network, API Service Provider, API Provider,
    Deployments, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-container-engine/master/_listings/google-container-engine/v1projectsprojectidzoneszoneclustersclusteridnodepoolsnodepoolid-get-openapi.md
- name: Google Container Engine - Set Cluster Node Management
  x-api-slug: v1projectsprojectidzoneszoneclustersclusteridnodepoolsnodepoolidsetmanagement-post
  description: Sets the NodeManagement options for a node pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/docker-container.png
  humanURL: https://cloud.google.com/container-engine/
  baseURL: ://container.googleapis.com//
  tags: Containers, Google APIs, Stack Network, API Service Provider, API Provider,
    Deployments, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-container-engine/master/_listings/google-container-engine/v1projectsprojectidzoneszoneclustersclusteridnodepoolsnodepoolidsetmanagement-post-openapi.md
- name: Google Container Engine - Rollback Node
  x-api-slug: v1projectsprojectidzoneszoneclustersclusteridnodepoolsnodepoolidrollback-post
  description: Roll back the previously Aborted or Failed NodePool upgrade. This will
    be an no-op if the last upgrade successfully completed.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/docker-container.png
  humanURL: https://cloud.google.com/container-engine/
  baseURL: ://container.googleapis.com//
  tags: Containers, Google APIs, Stack Network, API Service Provider, API Provider,
    Deployments, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-container-engine/master/_listings/google-container-engine/v1projectsprojectidzoneszoneclustersclusteridnodepoolsnodepoolidrollback-post-openapi.md
- name: Google Container Engine - Get Operations
  x-api-slug: v1projectsprojectidzoneszoneoperations-get
  description: Lists all operations in a project in a specific zone or all zones.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/docker-container.png
  humanURL: https://cloud.google.com/container-engine/
  baseURL: ://container.googleapis.com//
  tags: Containers, Google APIs, Stack Network, API Service Provider, API Provider,
    Deployments, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-container-engine/master/_listings/google-container-engine/v1projectsprojectidzoneszoneoperations-get-openapi.md
- name: Google Container Engine - Get Operations
  x-api-slug: v1projectsprojectidzoneszoneoperationsoperationid-get
  description: Gets the specified operation.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/docker-container.png
  humanURL: https://cloud.google.com/container-engine/
  baseURL: ://container.googleapis.com//
  tags: Containers, Google APIs, Stack Network, API Service Provider, API Provider,
    Deployments, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-container-engine/master/_listings/google-container-engine/v1projectsprojectidzoneszoneoperationsoperationid-get-openapi.md
- name: Google Container Engine - Create Operation
  x-api-slug: v1projectsprojectidzoneszoneoperationsoperationidcancel-post
  description: Cancels the specified operation.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/docker-container.png
  humanURL: https://cloud.google.com/container-engine/
  baseURL: ://container.googleapis.com//
  tags: Containers, Google APIs, Stack Network, API Service Provider, API Provider,
    Deployments, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-container-engine/master/_listings/google-container-engine/v1projectsprojectidzoneszoneoperationsoperationidcancel-post-openapi.md
- name: Google Container Engine - Get Server Configuration
  x-api-slug: v1projectsprojectidzoneszoneserverconfig-get
  description: Returns configuration info about the Container Engine service.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/docker-container.png
  humanURL: https://cloud.google.com/container-engine/
  baseURL: ://container.googleapis.com//
  tags: Containers, Google APIs, Stack Network, API Service Provider, API Provider,
    Deployments, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-container-engine/master/_listings/google-container-engine/v1projectsprojectidzoneszoneserverconfig-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://google.consumer.surveys.api.gallery.streamdata.io
- type: x-api-stack
  url: http://google.container.engine.stack.network
- type: x-change-log
  url: https://cloud.google.com/container-engine/release-notes
- type: x-documentation
  url: https://cloud.google.com/container-engine/docs/
- type: x-getting-started
  url: https://cloud.google.com/container-engine/docs/quickstart
- type: x-guides
  url: https://cloud.google.com/container-engine/docs/how-to
- type: x-pricing
  url: https://cloud.google.com/container-engine/pricing
- type: x-schedule-maintenance
  url: https://cloud.google.com/container-engine/docs/scheduled-maintenance
- type: x-service-level-agreements
  url: https://cloud.google.com/container-engine/sla
- type: x-tutorials
  url: https://cloud.google.com/container-engine/docs/tutorials
- type: x-website
  url: https://cloud.google.com/container-engine/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---