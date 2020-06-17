# Introduction

> Welcome to the Relational Database Lessons! You will be using PostgreSQL for this section. It's an extremely popular open source relational database management systems (RDBMS). My goal is to teach you everything I can about it and relatational databases.

## L10 Start PostgreSQL

The first thing to do is start the database service so you can log in and play around with it. Your virtual machine comes with PostgreSQL (psql) installed. In order to start it, type this command into the terminal:

```bash
sudo service postgresql start
```

### L10S1

Start the PostgreSQL service

## L20 Login

The psql service is now running. In order to interact with it, you need to log in. Use this command to do so:

```bash
sudo -u postgres psql
```

The `-u` stand for `username`. This will log you in as `postgres`.

### L20S1

Log in to psql

## L30 View Databases

I noticed the prompt changed to `postgres=#`. That must mean you are connected to the service. First thing to do is see what databases are here.

Type `\l` into the prompt to **l**ist them.

If you don't see the prompt at the bottom after listing, it means there wasn't enough room to display all the information. Press `Enter` until you see the prompt again.

### L30S1

List the databases