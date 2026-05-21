# Restful Booker API Automation

## Project Overview

This project is an end-to-end API automation framework built using Postman and Newman for the Restful Booker API.

## Features

- Authentication testing
- CRUD API testing
- Request chaining
- Environment variables
- Negative testing
- Schema validation
- Newman CLI execution

## Tools Used

- Postman
- Newman
- Node.js

## Run Command

```bash
npx newman run "collections/Restful Booker API Suite.postman_collection.json" -e "environments/QA Environment.postman_environment.json"
```

## Covered APIs

- Auth API
- Booking API
- Ping Health API

# restful-booker-api-automation
