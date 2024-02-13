### Java Script demo

## create a code commit repo and add the files of java script file in to that repo

### aws-code-build-to-pipeline
create pipeline to deploy simple caluculater using amazon s3 bucket website hosting and on more project java program depployed in lambda


**create a code build project with some name and add source primay source provider which one yiur using like repository providers like github or code commit or bitbucket add that and that repo name**

**enviroment provide**
```
Provisioning model - on-demand
Environment image - managed images
compute -ec2
 operating system
 - linux system
 run time
 - standard
 image
below run time link
```
 select using below links
[runtime details](https://docs.aws.amazon.com/codebuild/latest/userguide/build-spec-ref.html/).

role name will be automatically created when your enter build project name

## in this build spec is plays imortant role without buildspec file we can't execte this entire file

Buildspec specifications
use a buildspec file
enter that created file name below it is in yaml format  remaining all default options

## create pipeline
```
step-1
enter pipeline name
pipeline type v2
remaing default options
role automatically created

step-2
select provider
code commit or git hub
select repo and branch
remaining default options

step-3
select build option
code commit or jenkins
if code commit means select region with project name

step-4
you can skip this option

review all and click ok it will create pipe line
```
it will be trriger  automatically 
