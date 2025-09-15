node {
    
    stage('git') {
        git 'https://github.com/developerAdreet/jenkinspractice.git'
    }
    
    stage('build') {
       sh 'mvn clean package'
    }
}