swagger: "2.0"
x-collection-name: Plentymarkets
x-complete: 1
info:
  title: plentymarkets REST-API
  description: the-plentymarkets-rest-api-expands-the-functionality-of-the-plentymarkets-cms-and-allows-access-to-resources-i-e--data-records-via-unique-uri-paths
  contact:
    name: plentymarkets
    url: https://forum.plentymarkets.com/c/rest-api
  version: 1.0.0
host: example.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /rest/newsletters:
    get:
      summary: List newsletter entries
      description: List newsletter entries.
      operationId: getRestNewsletters
      x-api-path-slug: restnewsletters-get
      responses:
        200:
          description: OK
      tags:
      - List
      - Newsletter
      - Entries
  /rest/newsletters/folders:
    get:
      summary: List newsletter folders
      description: List newsletter folders.
      operationId: getRestNewslettersFolders
      x-api-path-slug: restnewslettersfolders-get
      responses:
        200:
          description: OK
      tags:
      - List
      - Newsletter
      - Folders