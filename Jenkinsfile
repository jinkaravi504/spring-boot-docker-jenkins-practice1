node{
    stage('SCM checkout'){
        git 'https://github.com/jinkaravi504/spring-boot-docker.git'
    }
    stage('comiple-package'){
        def mvnHome= tool name: 'maven-3.8.6', type: 'maven'
        sh "${mvnHome}/bin/mvn package"
    }
}