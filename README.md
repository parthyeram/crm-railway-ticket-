# Customer Support Ticketing CRM

Full-stack React, Express, and MySQL customer support ticketing system.

## Run locally

1. Create the MySQL database and tables:

   ```bash
   mysql -u root -p < backend/schema.sql
   ```

2. Copy `.env.example` to `.env` and set your MySQL credentials.

3. Install and run:

   ```bash
   npm install
   npm run dev
   ```

## Production

The included `Dockerfile` builds the frontend and starts the Express server. Configure the `MYSQL_HOST`, `MYSQL_PORT`, `MYSQL_USER`, `MYSQL_PASSWORD`, and `MYSQL_DATABASE` environment variables on your hosting provider.
