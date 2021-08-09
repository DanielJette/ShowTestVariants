# Print applicationId on testVariant

Run `./gradlew app:tasks`


## AGP 4.2.2:

```
> Configure project :app

================================================================================
TestVariants:
         - com.danieljette.testvariants.demo.test
         - com.danieljette.testvariants.full.test
================================================================================
```

---

## AGP 7.0.0:

```
> Configure project :app

================================================================================
TestVariants:

FAILURE: Build failed with an exception.

* Where:
Build file '/Users/danieljette/DevSource/neo/ShowTestVariants/app/build.gradle' line: 50

* What went wrong:
A problem occurred configuring project ':app'.
> Cannot query the value of property 'applicationId' because configuration of project ':app' has not completed yet.
```

---

## AGP 7.1.0-alpha05

```
> Configure project :app

================================================================================
TestVariants:
         - com.danieljette.testvariants.demo.test
         - com.danieljette.testvariants.full.test
================================================================================
```

---

## AGP 7.1.0-alpha06


```
> Configure project :app

================================================================================
TestVariants:

FAILURE: Build failed with an exception.

* Where:
Build file '/Users/danieljette/DevSource/neo/ShowTestVariants/app/build.gradle' line: 50

* What went wrong:
A problem occurred configuring project ':app'.
> Cannot query the value of property 'applicationId' because configuration of project ':app' has not completed yet.

```
