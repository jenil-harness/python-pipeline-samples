## access-control

[To Pipeline](https://qa.harness.io/ng/account/px7xd_BFRCi-pfWPYXVjvw/module/ci/orgs/default/projects/Shivam/pipelines/P1RemoteTemplate/pipeline-studio?repoName=testrepo&connectorRef=GithubConnector&storeType=REMOTE)



```mermaid
graph LR
    hello --> world
    world --> again
    again --> hello
```


```mermaid
graph TD
A[Acme AI] -->|contains| B[NLP Service]
A -->|contains| C[Image Recognition Service]
B -->|exposes| D[Text Analysis API]
B -->|exposes| E[Language Translation API]
C -->|exposes| F[Image Classification API]
C -->|exposes| G[Object Detection API]
B -->|depends-on| H[NLP Database]
B -->|depends-on| I[NLP Server]
C -->|depends-on| J[Image Database]
C -->|depends-on| K[Image Processing Server]
```
