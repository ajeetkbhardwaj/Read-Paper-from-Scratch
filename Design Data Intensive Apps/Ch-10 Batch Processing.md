# Chapter-10 : Batch Processing

The modern data systems like database, caches, search, indexes, web servers and etc, data processing we send a request and queries as instruction and some time later system gives response as answers resp.

Online data systems

1. Web browser requesting a webpage
2. A service calling a remote api

response time of systems

www and https/rest api made request and response to build systems.

1. Services(online systems) : Response time is the primary measure of performance of the services and availability.
2. Batch Processing(Offline Systems) : It takes a large amount of data as input and runs a job to process it and produces output of data. these jobs take time thus batch jobs are often scheduled to run periodically. The primary measure of a batch job is throughput.
3. Stream Processing(Near-real-time Systems)

### Unix Batch processing :

![1732621159999](image/Ch-10BatchProcessing/1732621159999.png)

![1732621182852](image/Ch-10BatchProcessing/1732621182852.png)

![1732621201794](image/Ch-10BatchProcessing/1732621201794.png)

![1732621221927](image/Ch-10BatchProcessing/1732621221927.png)


### MapReduce and Distributed FileSystems

![1732621434940](image/Ch-10BatchProcessing/1732621434940.png)

![1732621942756](image/Ch-10BatchProcessing/1732621942756.png)

![1732622480149](image/Ch-10BatchProcessing/1732622480149.png)

### Beyond MapReduce

![1732622567584](image/Ch-10BatchProcessing/1732622567584.png)