Install the Oracle JDK Update 152 on a slim version of Oracle Linux 7.

## Build

```
docker build -t oracle/java8 .
```

## Usage

```
docker run -it --rm oracle/java8 java -version
```
