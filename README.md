## How to Run

### 1. change root url

Open `UrlUtils.java` in `src/main/groovy/io/reactivesw/data/util` directory, edit field `ROOTURL`, set it to api-gateway url.

### 2. compile project

```shell
gradle clean build
```

### 3. run project

```shell
java -jar build/libs/test-data.jar
```