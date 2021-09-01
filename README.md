# dbt_intro
This is a basic package used to connect to a Snowflake instance using Data Build Tool (dbt).
In the dbt_intro folder, the dbt_project.yml file specifies which profile to use - in this case, 'my-snowflake-db'. This profile & its credentials are located in the profiles.yml file. By default, this profile's file is created in the D:/Users/{username} directory and should be separate from the project files/repo. Fortunately for me, I have no login credentials for anybody to steal, but the yml file does show which params are required for Snowflake access.

By running this dbt project with viable snowflake credentials and db/warehouse information, the user can insert the two example models into the db + warehouse of their choice, under whichever role and schema are specified in the profiles.yml file.
