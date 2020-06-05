# SiteReliability

Bash scripts for Site Reliability class from PSU Spring 2019.

The project featured a hosted primary and secondary server on Google Cloud Platform.
Three scripts helped with the automation of the application:

1) NEW_DEV
Creates new development servers from stable production images

2) PROMOTE_DEV_TO_PROD
Pushes the development server to production and creates snapshots of both

3) ROLLBACK_PROD
Rollback production to development (for instances that bug was introduced from dev to prod)
