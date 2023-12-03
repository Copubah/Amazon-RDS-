# Amazon RDS
- Amazon RDS is a fully managed relational database service from Aws which simplifies the setup,operation and scaling of a relational database.

## Main features
- Managed service;takes care of routine database tasks such as backups,recovery,software updates etc
- Multiple Database Engines;supports various relational database engines like MySQL,PostgresSQL,MariaDB etc
- Scalibilty;users can easily scale up their database instances either vertically or horizontally and Multi-AZ deployments
- Automated Backups;provides automated daily backups and allows users to create manual snapshots of their databases and users can restore their databases to any specific moment within the backup retention period
- Monitoring and logging;users can monitor the performances of their databases using Amazon Cloudwatch metrics
- Security;it offers various security features including network isolation using Amazon VPC,IAM database authentication etc


## Steps
- Log in to your AWS account as a user and search for Amazon RDS and click on "Create database"
- Choose a database creation method,i am going to use Easy create and choose your preferred database,i am going with MySQL and DB instance size for demo purpose i choose the free tier
- You can either set a master password or auto generate a password,navigate to "view default settings for easy create"
- View default settings and view the configuration settings if they are editable after database is created and choose "Create database"
- After the database is created you can modify any configuration parameters to your liking or needs