# ST DART API ENGINE

**Steps to run this project locally:**

1. Add .env file
2. Change the configuration in the .env file
3. Run `docker compose up -d` command
4. Run `hasura metadata apply` command
5. Run `hasura migrate apply` command
<!-- 6. Run `hasura seed apply` command //NOT NEEDED -->
6. Run `hasura console` command
7. Add database connection to hasura using hasura UI (Use PG_DATABASE_URL from .env in hasura and add db name as st-dart-db)


**Steps to this maintain code:**

1. Make changes to the code
2. Group similar changes in one commit and add commit message for changes
4. Fetch changes from development branch in origin using `git pull origin development`
5. Push the code to your repo - `git push origin (branch-name)`