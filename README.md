# python-web-bottle-api-sqlserver-simple

## Description
Simple web app that serves an api
for a bottle project.

Uses sqlalchemy query a table `dog`.

## Tech stack
- python
  - bottle
  - sqlalchemy
- mssql

## Docker stack
- python:latest
- mcr.microsoft.com/mssql/server:2017-CU17-ubuntu

## To run
`sudo ./install.sh -u`
- [Endpoint at](http://localhost/dog)

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
[Bottle sqlalchemy setup](https://github.com/iurisilvio/bottle-sqlalchemy/blob/master/examples/basic.py)
