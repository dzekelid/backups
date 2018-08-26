---
name: Backupify
x-slug: backupify
description: ""
image: ""
x-kinRank: "7"
x-alexaRank: "0"
tags: Backups
created: "2018-08-25"
modified: "2018-08-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/backups/master/_listings/backupify/apis.md
specificationVersion: "0.14"
apis:
- name: Backupify - Retrieve a list of all backups for the specified backup_instance.
  x-api-slug: v1backup-instancesbackup-instance-idbackups-get
  description: Only backups belonging to backup_instances you have permission to manage
    can be retrieved. Records are returned in ascending order (by id), with a default
    of 20 per page. Links to the next, previous, first, and last pages can be found
    in the response headers.
  image: ""
  humanURL: http://backupify.com
  baseURL: https://api.backupify.com//
  tags: API Not Found, API Provider, Backups, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/backups/master/_listings/backupify/v1backup-instancesbackup-instance-idbackups-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/backups/master/_listings/backupify/v1backup-instancesbackup-instance-idbackups-get-openapi.md
- name: Backupify - Perform an immediate backup of the specified backup_instance
  x-api-slug: v1backup-instancesbackup-instance-idbackups-post
  description: Only backup_instances you have permission to manage can be backed up
  image: ""
  humanURL: http://backupify.com
  baseURL: https://api.backupify.com//
  tags: API Not Found, API Provider, Backups, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/backups/master/_listings/backupify/v1backup-instancesbackup-instance-idbackups-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/backups/master/_listings/backupify/v1backup-instancesbackup-instance-idbackups-post-openapi.md
- name: Backupify - Retrieve the active backup for the specified backup_instance if
    one exists
  x-api-slug: v1backup-instancesbackup-instance-idbackupsactive-get
  description: Only backups belonging to backup_instances you have permission to access
    can be retrieved
  image: ""
  humanURL: http://backupify.com
  baseURL: https://api.backupify.com//
  tags: API Not Found, API Provider, Backups, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/backups/master/_listings/backupify/v1backup-instancesbackup-instance-idbackupsactive-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/backups/master/_listings/backupify/v1backup-instancesbackup-instance-idbackupsactive-get-openapi.md
- name: Backupify - Retrieve the specified backup for the specified backup_instance
  x-api-slug: v1backup-instancesbackup-instance-idbackupsbackup-id-get
  description: Only backups belonging to backup_instances you have permission to access
    can be retrieved
  image: ""
  humanURL: http://backupify.com
  baseURL: https://api.backupify.com//
  tags: API Not Found, API Provider, Backups, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/backups/master/_listings/backupify/v1backup-instancesbackup-instance-idbackupsbackup-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/backups/master/_listings/backupify/v1backup-instancesbackup-instance-idbackupsbackup-id-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://azure.virtual.network.api.gallery.streamdata.io
- type: x-api-stack
  url: http://backupify.stack.network
- type: x-blog
  url: https://www.backupify.com/blog
- type: x-website
  url: http://backupify.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---