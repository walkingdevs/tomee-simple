**Testing**

    mvn clean test

**Running**

    mvn clean package tomee:run -DskipTests

**Shipping**

    mvn clean package tomee:exec -DskipTests
    docker build --rm -t app .

    # How to run docker?
    
    docker run --restart always -d \
               --name app \
               -v /var/logs/app:/logs \
               -p 8080:8080 \
               app

**Params**
    
    Root     /
    Binding  0.0.0.0
    Port     8080
    
    http://localhost:8080

**Jrebel**

    mvn clean package tomee:run -Prebel

CLI:

    # Awesome changes...
    mvn compile

IDEA:
    
    # Awesome changes...
    Build->Make project

Look at console, see message?, done.