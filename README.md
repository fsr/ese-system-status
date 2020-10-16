# ESE System Status

This repository contains the system status dashboard for the services used for the First Semester Introduction 2020. It's based on [Statusfy](https://github.com/juliomrqz/statusfy).

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
