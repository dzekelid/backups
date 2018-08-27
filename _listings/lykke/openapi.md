swagger: "2.0"
x-collection-name: Lykke
x-complete: 1
info:
  title: Wallet_Api
  version: 1.0.0
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