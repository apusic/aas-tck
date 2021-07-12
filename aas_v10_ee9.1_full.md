# TCK Results
As required by the [Eclipse Foundation Technology Compatibility Kit License](https://www.eclipse.org/legal/tck.php), following is a summary of the TCK results for releases of Jakarta EE full 9.1.

## AAS V10-EE9 Jakarta EE 9.1 TCK Certification Summary
* Product Name, Version and download URL (if applicable):

AAS V10-EE9

* Specification Name, Version and download URL:

[Jakarta EE Platform, 9](https://jakarta.ee/specifications/platform/9/)

* TCK Version, digital SHA-256 fingerprint and download URL:

[Jakarta EE Platform TCK 9.1.0](https://download.eclipse.org/ee4j/jakartaee-tck/jakartaee9/promoted/jakartaeetck-9.1.0.zip), SHA-256: 2157f31cfc49b8e6c3747270b4cc2a71fd63e79e8066c26a645db8d36305bf6a

* Public URL of TCK Results Summary:

[TCK results summary](https://github.com/apusic/aas-tck/blob/master/aas_v10_ee9.1_full.md)

* Any Additional Specification Certification Requirements:

Jakarta Contexts and Dependency Injection [cdi-tck-3.0.1-dist.zip](https://download.eclipse.org/jakartaee/cdi/3.0/cdi-tck-3.0.1-dist.zip), SHA-256: f0a3bdd81ea552ddf2c2a6cd2576f0d5ca45026665cb4a5c42606a58bf1c133d

Jakarta Bean Validation [beanvalidation-tck-dist-3.0.0.zip](https://download.eclipse.org/jakartaee/bean-validation/3.0/beanvalidation-tck-dist-3.0.0.zip), SHA-256: c975fd229df0c40947a9f0a69b779ec92bebb3d21e05fdc65fccc1d11ef5525b

Dependency Injection [jakarta.inject-tck-2.0.1-bin.zip](https://download.eclipse.org/jakartaee/dependency-injection/2.0/jakarta.inject-tck-2.0.1-bin.zip), SHA-256: 7853d02d372838f8300f5a18cfcc23011c9eb9016cf3980bba9442e4b1f8bfc6

Debugging [jakarta-debugging-tck-2.0.0.zip](https://download.eclipse.org/jakartaee/debugging/2.0/jakarta-debugging-tck-2.0.0.zip), SHA-256: 71999815418799837dc6f3d0dc40c3dcc4144cd90c7cdfd06aa69270483d78bc

* Java runtime used to run the implementation:

Oracle JDK 1.8.0_201-b09

* Summary of the information for the certification environment, operating system, cloud, …​:

Apache Derby, Linux, Ubuntu 20.04.2 LTS

## Test results

### appclient
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 50 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 50
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### assembly 
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 30 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 30
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### concurrency
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 205 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 205
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### connector
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 477 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 477
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************

```

### ejb
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 1793 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 1793
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### ejb30/assembly
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 51 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 51
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### ejb30/bb
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 1193 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 1193
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### ejb30/lite/appexception
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 365 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 365
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### ejb30/lite/async
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 300 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 300
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### ejb30/lite/basic
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 105 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 105
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### ejb30/lite/ejbcontext
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 50 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 50
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### ejb30/lite/enventry
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 10 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 10
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### ejb30/lite/interceptor
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 175 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 175
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### ejb30/lite/lookup
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 30 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 30
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### ejb30/lite/naming
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 54 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 54
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### ejb30/lite/nointerface
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 60 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 60
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### ejb30/lite/packaging
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 211 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 203
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 8
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************

   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 8 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 8
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************

```
### ejb30/lite/singleton
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 230 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 219
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 10
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 1
   [runcts] OUT => [javatest.batch] ********************************************************************************

   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 11 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 11
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### ejb30/lite/stateful
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 129 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 129
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### ejb30/lite/tx
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 358 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 323
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 35
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************

   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 35 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 35
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### ejb30/lite/view
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 95 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 95
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### ejb30/lite/xmloverride
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 30 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 30
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### ejb30/misc
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 100 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 100
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### ejb30/sec
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 99 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 99
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### ejb30/timer
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 178 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 178
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### ejb30/webservice
``` console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 3 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 3
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### ejb30/zombie
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 1 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 1
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### ejb32
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 825 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 825
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### el
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 667 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 667
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

## integration
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 18 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 18
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jacc
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 40 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 40
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jaspic
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 68 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 68
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### javaee
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 24 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 24
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### javamail
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 112 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 112
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jaxrs
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 2803 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 2803
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jbatch
```console
[javatest.batch] ********************************************************************************
[javatest.batch] Completed running 322 tests.
[javatest.batch] Number of Tests Passed      = 322
[javatest.batch] Number of Tests Failed      = 0
[javatest.batch] Number of Tests with Errors = 0
[javatest.batch] ********************************************************************************
```

### jdbc
```console
   [runcts] OUT => [javatest.batch] Completed running 4924 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 4924
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jms
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 3510 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 3510
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jpa
```console
   [runcts] OUT => [javatest.batch] Completed running 11027 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 11027
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jsf
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 5526 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 5526
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jsonb
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 1062 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 1062
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jsonp
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 744 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 744
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jsp
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 730 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 730
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jstl
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 541 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 541
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### jta
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 195 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 195
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### samples
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 12 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 12
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### securityapi
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 84 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 84
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```
### servlet
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 1730 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 1730
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### signaturetest
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 4 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 4
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### webservices12
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 242 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 242
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```


### webservices13
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 53 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 53
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### websocket
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 745 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 745
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### xa
```console
   [runcts] OUT => [javatest.batch] ********************************************************************************
   [runcts] OUT => [javatest.batch] Completed running 66 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 66
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
   [runcts] OUT => [javatest.batch] ********************************************************************************
```

### Dependency Injection
```console
[INFO] Running AASBootstrapTCK
[INFO] Tests run: 50, Failures: 0, Errors: 0, Skipped: 0, Time elapsed: 0.387 s - in AASBootstrapTCK
```

### Contexts and Dependency Injection 
```console
 [mvn.test] Tests run: 1794, Failures: 0, Errors: 0, Skipped: 0, Time elapsed: 2,387.487 sec
 [mvn.test] 
 [mvn.test] Results :
 [mvn.test] 
 [mvn.test] Tests run: 1794, Failures: 0, Errors: 0, Skipped: 0
```

### Bean Validation
```console
Tests run: 1045, Failures: 0, Errors: 0, Skipped: 0, Time elapsed: 334.503 sec - in TestSuite

Results :

Tests run: 1045, Failures: 0, Errors: 0, Skipped: 0
```

### Debugging 
```console
java  -cp debugging-tck-2.0.0.jar VerifySMAP Hello_jsp.class.smap 

Hello_jsp.class.smap is a correctly formatted SMAP

```




