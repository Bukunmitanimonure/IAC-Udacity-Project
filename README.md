# Deploy a high-availability web app using CloudFormation
Codes written in Udacity's Cloud DevOps Engineer Nanodegree Course. 

Deploy Infrastructure:

```
 ./create.sh BuksServer servers.yml server-parameters.json
```

Update Infrastructure:

```
./update.sh BuksServer servers.yml server-parameters.json
```

Clean up when you're done:

```
./delete.sh BuksServer