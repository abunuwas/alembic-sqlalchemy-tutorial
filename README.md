# Setting up Alembic with SQLAlchemy Tutorial

Code for my video tutorial [Setting up Alembic with SQLAlchemy](https://youtu.be/nt5sSr1A_qw).

This tutorial explains how to set up Alembic to manage migrations with SQLAlchemy. You'll also learn to add to or query data from the database using SQLAlchemy.

## What are SQLAlchemy and Alembic?

* *SQLAlchemy* is Python's most popular Object Relational Mapper (ORM). ORMs are frameworks that offer an object-oriented interface to your database tables. ORMs give you a layer of abstraction on top of SQL, so you don't have to write SQL queries by hand - instead, you just write code. ORMs also abstract away the differences between SQL engines, such as PostgreSQL and MySQL, so you can switch between one and the other without having to change your code. You can learn more about SQLAlchemy with its official documentation: https://www.sqlalchemy.org/.

* *Alembic* is a database migrations management framework. Alembic ensures that your database schemas accurately reflect the data models that you define with SQLAlchemy. You can learn more about Alembic with its official documentation: https://alembic.sqlalchemy.org/en/lat....
