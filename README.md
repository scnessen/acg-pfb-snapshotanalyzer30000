# snapshotanalyzer-3000

Demo Project for AWS EC2 instance snapshots

## About

This project is a demo that uses boto3 to manage AWS EC2 instance snapshots.

## Configure

snapshotanalyzer uses the configuration file created by the AWS cli.

`aws configure --profile snapshotanalyzer`

## Running

`pipenv run "snapshotanalyzer\snapshotanalyzer.py <command> <--project=PROJECT>"`

*command* is list, start, or stop
*project* is optional
