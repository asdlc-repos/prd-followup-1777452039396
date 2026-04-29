# Overview

A web service that returns the current server time in JSON format when you make an HTTP request to it.

# Personas

- Developer — calls the service to get the current time for their application.

# Features

- Make a GET request to an endpoint and receive the current time.
- The response comes back as JSON with the time in ISO 8601 format.
- The service includes the timezone in the response.
- Developers can call it from any HTTP client or browser.
- The endpoint is always available at a predictable URL path.