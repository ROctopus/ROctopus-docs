# Next working example
## Features

### client
\+ User authentication (account details)
##### Worker
1. Ask task
2. Run task
3. Return result (if error return error?)
4. Start/stop button

##### Origin
1. Verify .rocto file
2. Read & list grid & selectable rows
3. Send job to server
4. List available jobs
5. Get job status
6. Cancel job
7. Download results package
8. Remove files from server


\+ File association with .rocto


### rpackage
##### Programmer interface
1. Skeleton & open files
2. Check before pack
3. Create meta info for client
4. Pack job into .rocto file
5. results to list

\+ Add niter to params.R

##### Worker interface
evaluateTask?

### server
1. Create folders [ user/AS&@NMDS!L/Results , user/AS&@NMDS!L/ ]
2. Receive .rocto
3. Expand job to set of tasks in database
4. Send tasks to worker
5. Receive results & save to job folder
6. Package results & send to origin
7. Send job status upon request
8. Remove file folder

\+ send email when job done

## Timing
30/08/2017 - 23:59 /// full working example


# I show you mine you show me yours
Where to test timing?
evaluateTask
