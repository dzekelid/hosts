---
swagger: "2.0"
x-collection-name: Apigee
x-complete: 0
info:
  title: Apigee Edge Delete Organizations Name Environments Env Name Virtualhosts
    Virtualhost Name
  description: Deletes a specific virtual host in an environment.
  version: 1.0.0
host: api.enterprise.apigee.com
basePath: /v1/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /organizations/{org_name}/environments/{env_name}/virtualhosts:
    get:
      summary: Get Organizations Name Environments Env Name Virtualhosts
      description: Lists all virtual hosts in an environment.
      operationId: getOrganizationsOrgNameEnvironmentsEnvNameVirtualhosts
      x-api-path-slug: organizationsorg-nameenvironmentsenv-namevirtualhosts-get
      parameters:
      - in: path
        name: env_name
        description: Mention the environment name
      - in: path
        name: org_name
        description: Mention the organization name
      responses:
        200:
          description: OK
      tags:
      - Organizations
      - Environments
      - Env
      - Virtualhosts
    post:
      summary: Post Organizations Name Environments Env Name Virtualhosts
      description: Creates a virtual host.
      operationId: postOrganizationsOrgNameEnvironmentsEnvNameVirtualhosts
      x-api-path-slug: organizationsorg-nameenvironmentsenv-namevirtualhosts-post
      parameters:
      - in: query
        name: Content-Type
        description: Specify the content type
      - in: path
        name: env_name
        description: Mention the environment name
      - in: path
        name: org_name
        description: Mention the organization name
      responses:
        200:
          description: OK
      tags:
      - Organizations
      - Environments
      - Env
      - Virtualhosts
  /organizations/{org_name}/environments/{env_name}/virtualhosts/{virtualhost_name}:
    get:
      summary: Get Organizations Name Environments Env Name Virtualhosts Virtualhost
        Name
      description: Gets details for a named virtual host .
      operationId: getOrganizationsOrgNameEnvironmentsEnvNameVirtualhostsVirtualhostName
      x-api-path-slug: organizationsorg-nameenvironmentsenv-namevirtualhostsvirtualhost-name-get
      parameters:
      - in: path
        name: env_name
        description: Mention the environment name
      - in: path
        name: org_name
        description: Mention the organization name
      - in: path
        name: virtualhost_name
        description: Mention the virtual host name
      responses:
        200:
          description: OK
      tags:
      - Organizations
      - Environments
      - Env
      - Virtualhosts
      - Virtualhost
    post:
      summary: Post Organizations Name Environments Env Name Virtualhosts Virtualhost
        Name
      description: Updates a specific virtual host in an environment.
      operationId: postOrganizationsOrgNameEnvironmentsEnvNameVirtualhostsVirtualhostName
      x-api-path-slug: organizationsorg-nameenvironmentsenv-namevirtualhostsvirtualhost-name-post
      parameters:
      - in: query
        name: Content-Type
        description: Specify the content type
      - in: path
        name: env_name
        description: Mention the environment name
      - in: path
        name: org_name
        description: Mention the organization name
      - in: path
        name: virtualhost_name
        description: Mention the virtual host name
      responses:
        200:
          description: OK
      tags:
      - Organizations
      - Environments
      - Env
      - Virtualhosts
      - Virtualhost
    delete:
      summary: Delete Organizations Name Environments Env Name Virtualhosts Virtualhost
        Name
      description: Deletes a specific virtual host in an environment.
      operationId: deleteOrganizationsOrgNameEnvironmentsEnvNameVirtualhostsVirtualhostName
      x-api-path-slug: organizationsorg-nameenvironmentsenv-namevirtualhostsvirtualhost-name-delete
      parameters:
      - in: path
        name: env_name
        description: Mention the environment name
      - in: path
        name: org_name
        description: Mention the organization name
      - in: path
        name: virtualhost_name
        description: Mention the virtual host name
      responses:
        200:
          description: OK
      tags:
      - Organizations
      - Environments
      - Env
      - Virtualhosts
      - Virtualhost
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---