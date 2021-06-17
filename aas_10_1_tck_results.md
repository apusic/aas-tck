# TCK Results
As required by the [Eclipse Foundation Technology Compatibility Kit License](https://www.eclipse.org/legal/tck.php), following is a summary of the TCK results for releases of Jakarta EE Platform, Full Profile.

## AAS 10.1 Full Profile Certification Summary
Product Name, Version and download URL (if applicable):  
[AAS 10.1](http://www.apusic.com/info_safety/server)

Specification Name, Version and download URL:

[Jakarta EE Platform, Full Profile 8](https://jakarta.ee/specifications/platform/8/)
TCK Version, digital SHA-256 fingerprint and download URL:

[Jakarta EE Platform CTS 8.0.2](http://download.eclipse.org/jakartaee/platform/8/eclipse-jakartaeetck-8.0.2.zip) , SHA-256: 14a21b617bb646055c2952f1422ec04a71389fb37301e1c2969f6c3700aee965

Public URL of TCK Results Summary:

[https://github.com/apusic/aas-tck/blob/master/aas_10_1_tck_results.md](https://github.com/apusic/aas-tck/blob/master/aas_10_1_tck_results.md)


Any Additional Specification Certification Requirements:

Jakarta Dependency Injection 1.0 TCK

See test results in section di.
Download URL & SHA-256: [jakarta.inject-tck-1.0-bin.zip](https://download.eclipse.org/jakartaee/dependency-injection/1.0/jakarta.inject-tck-1.0-bin.zip), SHA-256: b679bac9b1057df894753892a880ba6ade530607dd811157106ed767aa26481f

Jakarta Contexts and Dependency Injection 2.0 TCK

See test results in section cdi.
Download URL & SHA-256: [cdi-tck-2.0.6-dist.zip](https://download.eclipse.org/jakartaee/cdi/2.0/cdi-tck-2.0.6-dist.zip), SHA-256: 75e969a7a3b3c77332154a2008309aad821a923d8684139242048a7640762808

Jakarta Bean Validation 2.0 TCK,

See test results in section beanvalidation.
[beanvalidation-tck-dist-2.0.5.zip](https://download.eclipse.org/jakartaee/bean-validation/2.0/beanvalidation-tck-dist-2.0.5.zip), SHA-256: b6778914f78bfcce5d6934347d71502603b1b0a6bbfdfbcf956271c367d40974

Jakarta Batch 1.0 TCK tests are included in Jakarta EE 8 CTS tests, See test results in section jbatch

Java SE Provider & Version tested with:

OracleJDK Java(TM) SE Runtime Environment (build 1.8.0_201-b09)

OS version:

Ubuntu 18.04.4 LTS (Bionic Beaver)

Database:

Apache Derby 10.14.2.0 


## Test results

### appclient
```console
[runcts] OUT => [javatest.batch] Completed running 50 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 50
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
```

### assembly
```console
   [runcts] OUT => [javatest.batch] Completed running 30 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 30
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
```

### compat12
```console
   [runcts] OUT => [javatest.batch] Completed running 12 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 12
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
```
### compat13
```console
   [runcts] OUT => [javatest.batch] Completed running 15 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 15
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
```
### concurrency
```console
   [runcts] OUT => [javatest.batch] Completed running 205 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 205
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
```

### connector
```console
   [runcts] OUT => [javatest.batch] Completed running 495 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 495
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
```

### ejb
```console
   [runcts] OUT => [javatest.batch] Completed running 1809 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 1809
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
```

### ejb30/assembly
```console
   [runcts] OUT => [javatest.batch] Completed running 51 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 51
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
```

### ejb30/bb
```console
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 1200
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
```

### ejb30/lite/appexception
```console
   [runcts] OUT => [javatest.batch] Completed running 365 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 365
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
```
### ejb30/lite/async
```console
   [runcts] OUT => [javatest.batch] Completed running 300 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 300
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
```

### ejb30/lite/basic
```console
   [runcts] OUT => [javatest.batch] Completed running 105 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 105
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
```

### ejb30/lite/ejbcontext
```console
   [runcts] OUT => [javatest.batch] Completed running 50 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 50
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
```

### ejb30/lite/enventry
```console
   [runcts] OUT => [javatest.batch] Completed running 30 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 30
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
```

### ejb30/lite/interceptor
```console
   [runcts] OUT => [javatest.batch] Completed running 175 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 175
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
```

### ejb30/lite/lookup
```console
   [runcts] OUT => [javatest.batch] Completed running 30 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 30
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
```

### ejb30/lite/naming
```console
   [runcts] OUT => [javatest.batch] Completed running 54 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 54
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
```

### ejb30/lite/nointerface
```console
   [runcts] OUT => [javatest.batch] Completed running 60 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 60
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
```

### ejb30/lite/packaging
```console
   [runcts] OUT => [javatest.batch] Completed running 211 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 211
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
```

### ejb30/lite/singleton
```console
   [runcts] OUT => [javatest.batch] Completed running 230 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 230
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
```

### ejb30/lite/stateful
```console
   [runcts] OUT => [javatest.batch] Completed running 129 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 129
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
```
### ejb30/lite/tx
```console
   [runcts] OUT => [javatest.batch] Completed running 358 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 358
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
```

### ejb30/lite/view
```console
   [runcts] OUT => [javatest.batch] Completed running 95 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 95
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
```

### ejb30/lite/xmloverride
```console
   [runcts] OUT => [javatest.batch] Completed running 30 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 30
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
```

### ejb30/misc
```console
   [runcts] OUT => [javatest.batch] Completed running 100 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 100
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
```

### ejb30/sec
```console
   [runcts] OUT => [javatest.batch] Completed running 99 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 99
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
```

### ejb30/timer
```console
   [runcts] OUT => [javatest.batch] Completed running 178 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 178
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
```

### ejb30/webservice
```console
   [runcts] OUT => [javatest.batch] Completed running 3 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 3
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
```

### ejb30/zombie
```console
   [runcts] OUT => [javatest.batch] Completed running 1 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 1
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
```

### ejb32
```console
   [runcts] OUT => [javatest.batch] Completed running 825 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 825
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
```

### el
```console
   [runcts] OUT => [javatest.batch] Completed running 667 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 667
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
```

### integration
```console
   [runcts] OUT => [javatest.batch] Completed running 18 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 18
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
```

### interop
```console
   [runcts] OUT => [javatest.batch] Completed running 820 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 820
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
```

### j2eetools
```console
   [runcts] OUT => [javatest.batch] Completed running 134 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 134
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
```

### jacc
```console
   [runcts] OUT => [javatest.batch] Completed running 40 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 40
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
```

### jaspic
```console
   [runcts] OUT => [javatest.batch] Completed running 68 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 68
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
```

### javaee
```console
   [runcts] OUT => [javatest.batch] Completed running 24 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 24
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
```

### javamail
```console
   [runcts] OUT => [javatest.batch] Completed running 112 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 112
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
```

### jaxr
```console
   [runcts] OUT => [javatest.batch] Completed running 1372 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 1372
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
```

### jaxrpc
```console
   [runcts] OUT => [javatest.batch] Completed running 1478 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 1478
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
```

### jaxrs
```console
   [runcts] OUT => [javatest.batch] Completed running 2803 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 2803
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
```
### jdbc
```console
   [runcts] OUT => [javatest.batch] Completed running 4924 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 4924
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
```

### jms
```console
   [runcts] OUT => [javatest.batch] Completed running 3510 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 3510
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
```

### jpa
```console
   [runcts] OUT => [javatest.batch] Completed running 11027 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 11027
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
```

### jsf
```console
   [runcts] OUT => [javatest.batch] Completed running 5526 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 5526
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
```

### jsonb
```console
   [runcts] OUT => [javatest.batch] Completed running 1062 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 1062
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
```

### jsonp
```console
   [runcts] OUT => [javatest.batch] Completed running 744 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 744
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
```

### jsp
```console
   [runcts] OUT => [javatest.batch] Completed running 731 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 731
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
```

### jstl
```console
   [runcts] OUT => [javatest.batch] Completed running 541 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 541
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
```

### jta 
```console
   [runcts] OUT => [javatest.batch] Completed running 195 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 195
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
```

### rmiiiop
```console
   [runcts] OUT => [javatest.batch] Completed running 129 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 129
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
```

### samples
```console
   [runcts] OUT => [javatest.batch] Completed running 13 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 13
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
```

### securityapi
```console
   [runcts] OUT => [javatest.batch] Completed running 84 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 84
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
```

### servlet
```console
   [runcts] OUT => [javatest.batch] Completed running 1746 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 1746
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
```

### signaturetest
```console
   [runcts] OUT => [javatest.batch] Completed running 5 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 5
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
```

### webservices
```console
   [runcts] OUT => [javatest.batch] Completed running 507 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 507
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
```

### webservices12
```console
   [runcts] OUT => [javatest.batch] Completed running 242 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 242
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
```

### webservice13
```console
   [runcts] OUT => [javatest.batch] Completed running 53 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 53
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
```

### websocket
```console
   [runcts] OUT => [javatest.batch] Completed running 745 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 745
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
```

### xa
```console
   [runcts] OUT => [javatest.batch] Completed running 66 tests.
   [runcts] OUT => [javatest.batch] Number of Tests Passed      = 66
   [runcts] OUT => [javatest.batch] Number of Tests Failed      = 0
   [runcts] OUT => [javatest.batch] Number of Tests with Errors = 0
```

### beanvalidation
```console
Tests run: 1043, Failures: 0, Errors: 0, Skipped: 0, Time elapsed: 715.013 sec - in TestSuite

Results :

Tests run: 1043, Failures: 0, Errors: 0, Skipped: 0
```

### cdi
```console
Tests run: 1805, Failures: 0, Errors: 0, Skipped: 0, Time elapsed: 1,789.375 sec

Results :

Tests run: 1805, Failures: 0, Errors: 0, Skipped: 0
```

### di
```console
[INFO] Tests run: 50, Failures: 0, Errors: 0, Skipped: 0, Time elapsed: 1.092 sec
```

### jbatch
```console
[javatest.batch] Completed running 322 tests.
[javatest.batch] Number of Tests Passed      = 322
[javatest.batch] Number of Tests Failed      = 0
[javatest.batch] Number of Tests with Errors = 0
```