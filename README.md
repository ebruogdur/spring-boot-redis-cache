
# Clone source code from git
$ git clone https://github.com/ebruogdur/spring-boot-redis-cache.git

# Run Redis Image
$ docker run -p 6379:6379 --name redisserver -d redis .

# Build project with Maven
$ mvn clean install

http://localhost:8080/test




