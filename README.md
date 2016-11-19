#My Personal Teaching Assistant#

##Setup##

Install the following:

- Node.js (4.X or greater) and npm
- `gcloud` (https://cloud.google.com/sdk/downloads)
- Google Cloud API account and project with billing

##Getting Started##

- Setup up an account with Google Cloud API and a project with billing
- Initialize `gcloud`

```
gcloud init
```

- Get auth key

```
gcloud auth activate-service-account --key-file=@YOUR-KEY-FILE-PATH
gcloud auth print-access-token
```

- To see how a syllabus is parsed, replace `@YOUR-ACCESS-TOKEN` with your auth key and run `scripts/parse-syllabus.sh`