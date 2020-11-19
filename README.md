# ESE System Status

This repository contains the system status dashboard for the services used for the First Semester Introduction 2020. It's based on [Statusfy](https://github.com/juliomrqz/statusfy).

## Re-enabling the Workflow

As the ESE 2020 is over by now, this workflow has been disabled. To re-enable it, grab a ssh-accessible host you want to put the service overview onto and modify the secrets in th erepository settings so that deploying to that machine works (you need a RSA SSH key without password and the correct `known_hosts` string for the target server).
Then move the `main.yml` file from `.github/disabled-workflows` back into the `workflows` directory and edit it accordingly.

## Setup

The status page itself is a static page, meaning it has to be updated locally. To get started, clone this repository and install the dependencies:

```bash
git clone git@github.com:fsr/ese-system-status
cd ese-system-status
npm install
```

## Adding a new incident

To add a new incident, run:
```bash
npm run new-incident
```

If you want, you can check the results using npm run dev and then commit the changes to this repository. The status page will be updated automatically.

## Documentation
The documentation for Statusfy incidents can be found [here](https://docs.statusfy.co/guide/incidents/).
