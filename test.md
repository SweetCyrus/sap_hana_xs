## Adding a new environment

To add a new environment, for example, like `mkt`, please follow the following steps:

- Add the alias in the terraform project.
- Create the configuration files in the helm project.
- Create the database in the corresponding RDS instance (staging and production).
  - In the newly created database, make yourself admin.
```sql