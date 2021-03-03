# artifact-server

An Express server intended to simulate the Github Artifact Server functionality to be paired with the [`nektos/act`](https://github.com/nektos/act) application, which offers Github Actions testing in your local environment.

## Deployment
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/Reviewable/artifact-server/tree/main)

## Environment Variables
```
ACTIONS_RUNTIME_TOKEN = { ACCESS_TOKEN }
ACTIONS_RUNTIME_URL = { ARTIFACTS_SERVER_URL }
```
