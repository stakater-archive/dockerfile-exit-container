# dockerfile-exit-container
Simple container that exit's based on the given exit code through environmental varaibles.

It is used for testing services that depend on a container's exit code.

Usage:
Default exit code = 0
```
docker run -i stakater/exit-container
```

```
docker run -d -e EXIT_CODE=1 stakater/exit-container
```