---
swagger: "2.0"
x-collection-name: Lykke
x-complete: 0
info:
  title: Lykke Add API Privatewalletbackup
  version: 1.0.0
  description: Add api privatewalletbackup.
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/BackupCompleted:
    post:
      summary: Add API Backup Completed
      description: Add api backup completed.
      operationId: ApiBackupCompletedPost
      x-api-path-slug: apibackupcompleted-post
      parameters:
      - in: header
        name: Authorization
        description: access token
      responses:
        200:
          description: OK
      tags:
      - Backup
      - Completed
  /api/PrivateWalletBackup:
    post:
      summary: Add API Privatewalletbackup
      description: Add api privatewalletbackup.
      operationId: ApiPrivateWalletBackupPost
      x-api-path-slug: apiprivatewalletbackup-post
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: body
        name: backupModel
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Privatewalletbackup
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