node {
    stage('Clean'){
        'mvn clean'
    }
    stage('Validate'){
        'mvn validate'
    }
    stage('Compile'){
        'mvn compile'
    }
    stage('Test'){
        'mvn test -DskipTests'
    }
    stage('Package'){
        'mvn package -DskipTests'
    }
    stage('Verfiy'){
        'mvn verify -DskipTests'
    }
    stage('Install'){
        'mvn Install -DskipTests'
    }
}
