# snapshotalyzer-30000
Demo project

## ABOUT
boto3 used to manage AWS EC2 instance snapshots

## Configuring
shotty uses the configuration file created by the AWS cli. e.g.

`aws configure --profile shotty`

## Running

`pipenv run python shotty/shotty.py <command> <subcommand> <--project=PROJECT>`

*command* is instances, volumes, or snapshots
*subcommand* - depends on command list, start, stop
*project* is optional
