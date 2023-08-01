# Gradelified CDKTF Project

An experiment to see if moving CDKTF Java projects from maven to gradle improves synth-time performance.

## Run

```
cdktf get
./gradlew run # should take the normal amount of time
./gradlew run # should be faster (even if you change the content of the main stack)
```
