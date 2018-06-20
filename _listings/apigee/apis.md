---
name: Apigee
x-slug: apigee
description: Apigee Edge is a platform for developing and managing API proxies. Think
  of a proxy as an abstraction layer that fronts for your backend service APIs and
  provides value-added features like security, rate limiting, quotas, analytics, and
  more. The primary consumers of Edge API proxies are app developers who want to use
  your backend services.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
x-kinRank: "8"
x-alexaRank: "0"
tags: Hosts
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/hosts/master/_listings/apigee/apis.md
specificationVersion: "0.14"
apis:
- name: Apigee Edge Get Organizations Name Environments Env Name Virtualhosts
  x-api-slug: apigee-edge
  description: Lists all virtual hosts in an environment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/environments/{env_name}/virtualhosts
  tags: Organizations,Environments,Env,Virtualhosts
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hosts/master/_listings/apigee/organizationsorg-nameenvironmentsenv-namevirtualhosts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hosts/master/_listings/apigee/organizationsorg-nameenvironmentsenv-namevirtualhosts-get-openapi.md
- name: Apigee Edge Post Organizations Name Environments Env Name Virtualhosts
  x-api-slug: apigee-edge
  description: Creates a virtual host.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/environments/{env_name}/virtualhosts
  tags: Organizations,Environments,Env,Virtualhosts
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hosts/master/_listings/apigee/organizationsorg-nameenvironmentsenv-namevirtualhosts-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hosts/master/_listings/apigee/organizationsorg-nameenvironmentsenv-namevirtualhosts-post-openapi.md
- name: Apigee Edge Get Organizations Name Environments Env Name Virtualhosts Virtualhost
    Name
  x-api-slug: apigee-edge
  description: Gets details for a named virtual host .
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/environments/{env_name}/virtualhosts/{virtualhost_name}
  tags: Organizations,Environments,Env,Virtualhosts,Virtualhost
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hosts/master/_listings/apigee/organizationsorg-nameenvironmentsenv-namevirtualhostsvirtualhost-name-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hosts/master/_listings/apigee/organizationsorg-nameenvironmentsenv-namevirtualhostsvirtualhost-name-get-openapi.md
- name: Apigee Edge Post Organizations Name Environments Env Name Virtualhosts Virtualhost
    Name
  x-api-slug: apigee-edge
  description: Updates a specific virtual host in an environment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/environments/{env_name}/virtualhosts/{virtualhost_name}
  tags: Organizations,Environments,Env,Virtualhosts,Virtualhost
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hosts/master/_listings/apigee/organizationsorg-nameenvironmentsenv-namevirtualhostsvirtualhost-name-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hosts/master/_listings/apigee/organizationsorg-nameenvironmentsenv-namevirtualhostsvirtualhost-name-post-openapi.md
- name: Apigee Edge Delete Organizations Name Environments Env Name Virtualhosts Virtualhost
    Name
  x-api-slug: apigee-edge
  description: Deletes a specific virtual host in an environment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/environments/{env_name}/virtualhosts/{virtualhost_name}
  tags: Organizations,Environments,Env,Virtualhosts,Virtualhost
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hosts/master/_listings/apigee/organizationsorg-nameenvironmentsenv-namevirtualhostsvirtualhost-name-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hosts/master/_listings/apigee/organizationsorg-nameenvironmentsenv-namevirtualhostsvirtualhost-name-delete-openapi.md
- name: Apigee Edge
  x-api-slug: apigee-edge
  description: Apigee Edge is a platform for developing and managing API proxies.
    Think of a proxy as an abstraction layer that fronts for your backend service
    APIs and provides value-added features like security, rate limiting, quotas, analytics,
    and more. The primary consumers of Edge API proxies are app developers who want
    to use your backend services.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1/
  tags: Hosts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/hosts/master/_listings/apigee/openapi.md
x-common:
- type: x-website
  url: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---