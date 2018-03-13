---
swagger: "2.0"
info:
  title: ParallelDots AI APIs Docs
  description: Our powerful Deep Learning powered APIs can comprehend a huge amount
    of unstructured text and visual content to empower your products.
  version: 1.0.0
host: apis.paralleldots.com
basePath: /v3
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /custom_classifier:
    post:
      summary: Custom Classifier
      description: |-
        # Introduction
        What does your API do?

        Custom Classifier API accepts input text, categories with a list of sub-categories and API key to return a JSON response classifying the input text into categories provided
      operationId: CustomClassifierPost
      parameters:
      - in: formData
        name: api_key
      - in: formData
        name: category
      - in: formData
        name: text
      responses:
        200:
          description: OK
      tags:
      - machine learning
      - custom
      - classifier
definitions: []
x-collection-name: ParallelDots
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