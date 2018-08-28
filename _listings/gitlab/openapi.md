swagger: "2.0"
x-collection-name: GitLab
x-complete: 1
info:
  title: API title
  version: 1.0.0
host: localhost:3000
basePath: /api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v3/projects/{id}/services/custom-issue-tracker:
    put:
      summary: Put Projects Services Custom Issue Tracker
      description: Set custom-issue-tracker service for project
      operationId: putV3ProjectsIdServicesCustomIssueTracker
      x-api-path-slug: v3projectsidservicescustomissuetracker-put
      parameters:
      - in: formData
        name: description
        description: Description
      - in: path
        name: id
      - in: formData
        name: issues_url
        description: Issues URL
      - in: formData
        name: new_issue_url
        description: New issue URL
      - in: formData
        name: project_url
        description: Project URL
      - in: formData
        name: push_events
        description: Event will be triggered by a push to the repository
      - in: formData
        name: title
        description: Title
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Services
      - Custom
      - Issue
      - Tracker