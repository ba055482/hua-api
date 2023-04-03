# Final project of Web information systems and IoT

## Overview

This is the backend component of the application. It is implemented in Java, using Spring framework.  
The reason we selected this technology stack is because of prior experience on Java/Spring.
Its purpose is to handle HTTP requests originating from the [UI component](https://github.com/geokall/hua-ui) and
perform basic CRUD operations.

Below are enlisted some key points:

- Authentication is implemented with JWT.
- Data are persisted on a PostgreSQL database, which is not part of this project.
- Tests use the H2 (in-memory) database for simplicity.
- No embedded web servers are used.

You can use `docker-compose` to deploy the application with a database as a container locally.