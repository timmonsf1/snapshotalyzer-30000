# find-close-meteorites
A demo project that uses Python and NASA data to find meteor landing sites

##About 
This project is a demo and uses boto3 to manage AWS EC2 instance snapshots.

##Configuring

shotty uses the configuration file created by the AWS cli. e.g.

'aws configure --profile shotty'

## Running

This project requires Python 3 and the requests packageself.

'python3 find_meteors.py'

'pipenv run "python shotty/shotty.py <command>
<--project=PROJECT>"'

*command* is list, start, or stop
*project* is optional
```
pipenv install
pipenv run "python find_meteors.py"

```
