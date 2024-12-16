#This repo is only a copy for educational purposes and all credits for owner of original repo - https://github.com/nanuchi/my-project

##### build the project

    ./gradlew build

##### build Docker image called java-app. Execute from root

    docker build -t java-app .
    
##### push image to repo 

    docker tag java-app demo-app:java-1.0
    
