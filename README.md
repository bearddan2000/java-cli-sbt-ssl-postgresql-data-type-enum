# java-cli-sbt-ssl-postgresql-data-type-enum

## Description
Creates a small database table
called `dog`. Uses an enum user defined type.

Uses self-sign ssl.

## Tech stack
- java
- sbt
  - 6.8.2

## Docker stack
- alpine:edge
- postgresql:alpine
- hseeberger/scala-sbt:11.0.2-oraclelinux7_1.3.5_2.12.10

## To run
`sudo ./install.sh -u`

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`
