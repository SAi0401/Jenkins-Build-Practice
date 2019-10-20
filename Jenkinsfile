pipeline{
    stage('GIT') {
        sh 'https://github.com/SAi0401/Jenkins-Build-Practice.git'
    }
    stage('package') {
        sh 'mvn package'
    }
    stage('archiveartifacts'){
        archive 'gameoflife-web/target/*.war'
    }
}