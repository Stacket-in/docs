# Database Configuration

There are two database configurations available:

1. **Development**: This is the database used while developing the application. This is run locally and seeding the database is done with local data.
2. **Production**: This is the database used in production. This is run on the server and seeding the database is done with remote data.

Be careful when changing the database configuration. If you change the database configuration, you will lose all your data.

## Setting up development database

This step assumes that you have already installed postgresql and created a user with the following credentials:

    username: postgres
    password: admin

After creating the user with above credentials we will start the server on port 5432. Hence the following command will start the server:

    sudo service postgresql start
