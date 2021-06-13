# Business Meeting Meetings API

## Publishing Overview

This document contains additional info required for publishing

## Evnironment Variables

The following environment variables are required for running this project:

- `DB_NAME`: Name of database to connect to. \
  Variable used in [mongoDbSource.ts](https://github.com/SudoDevOSS/business-meeting-meetings-api/blob/master/src/data/source/mongoDbSource.ts)
- `DB_SOURCE`: Db server url, must be this format `mongo://URL:PORT` (omit port if you are using default `27017`).\
  Variable used in [mongoDbSource.ts](https://github.com/SudoDevOSS/business-meeting-meetings-api/blob/master/src/data/source/mongoDbSource.ts)
- `PORT`: default port to listen to. Variable used in [app.ts](https://github.com/SudoDevOSS/business-meeting-meetings-api/blob/master/app.ts)
