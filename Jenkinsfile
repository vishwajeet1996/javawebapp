node {
   def mvnHome
   stage('Prepare') {
      git url: 'https://github.com/kesavkummari/javawebapp.git', branch: 'main'
      mvnHome = tool 'maven'
    }

    stage('Clean'){
       sh '${mvnHome}/bin/mvn -Dmaven.test.failure.ignore clean'
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
