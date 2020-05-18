# SmartDoor

![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen) ![Python](https://upload.wikimedia.org/wikipedia/commons/3/34/Blue_Python_3.6_Shield_Badge.svg)

SmartDoor is a distributed system that authenticates people and provides them with access to a virtual door using AWS services like Kinesis Video Streams, Amazon Rekognition and rest of the AWS stack.

## Architecture

![SmartDoor](https://github.com/NikhilNar/SmartDoor/blob/master/architecture.png)

## Deployment

### Package:
aws cloudformation package --template-file template.yml --s3-bucket cc-smartdoor --output-template-file output-template.yml

### Deploy:
aws cloudformation deploy --template-file output-template.yml --capabilities CAPABILITY_IAM --stack-name smart-door

## Application Preview

### Authorize visitor (WP1):

![Authorize-visitor](https://github.com/NikhilNar/SmartDoor/blob/master/authorize-visitor.png)

### Authenticate visitor (WP2): 

![Authenticate-visitor](https://github.com/NikhilNar/SmartDoor/blob/master/authenticate-visitor.png)

## Team

* [Nikhil Nar](https://github.com/NikhilNar)
* [Suraj Gaikwad](https://github.com/surajgovardhangaikwad)
* [Chinmay Wyawahare](https://github.com/gandalf1819)
