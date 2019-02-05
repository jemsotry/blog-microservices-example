# blog-microservices-example


###Step 1: Build all projects

Build all project

```bash
$ cd blog-microservices-example
$ ./build-all.sh
```

It should result in 6 log messages it will be saying:

###Step 2: Start all projects

BUILD SUCCESSFUL

Start all projects

```bash
$ ./start-all.sh
```

###Step 3: Validating Edge Server and Service Discovery

http://localhost:8761

###Step 4: Test product composite


```bash
$ curl -s localhost:8765/productcomposite/product/1
```
