# TODO

- security: encrypt the .pem files before storing them into GH actions cache
- address TODO found in this repo;
- display deployments which aren't part of the state (`.akash/{DSEQ,PROVIDER}`);
- add a workflow for sending AKT tokens to akash1... address;
- add a workflow for displaying akash1... address (+QR);
- add a GH action cronjob to monitor the docker image (on docker hub / ghcr.io / ...) and update+deploy the deploy.sdl
- add a GH action cronjob to monitor the funds and email / text when running low
- add a GH action cronjob to monitor the funds and automatically deposit (to keep the margin: `DEPOSIT` >= `MIN_DEPOSIT`)
