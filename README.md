<<<<<<< HEAD
# test-github-actions-java-gradle
=======
##### build the project

    ./gradlew build

##### build Docker image called java-app. Execute from root

    docker build -t java-app .
    
##### push image to repo 

    docker tag java-app demo-app:java-1.0
    
>>>>>>> 387019b (added gradle code)
