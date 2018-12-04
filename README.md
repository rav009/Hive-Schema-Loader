# Hive-Schema-Loader
A Kettle Project which enable you to get the schema of a hive db in format of hql.

- Use Kettle to configure the connection in the both ktr files.
- Use Kettle to open the "Loop database output DDL.kjb", and input the database name in parameters and execute the job.
- Execute the job and you will find the schema in the folder of this project with name same as the database name.
