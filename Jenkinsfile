node {
    stage ('SCM') {
    git credentialsId: 'Github-SAI', url: 'https://github.com/cherukurisai451/maven_demo.git'    
    }
    stage ('Build') {
        sh 'mvn clean package'
    }
    stage ('test-cases') {
        echo 'test'
    }
    stage ('deploy'){
        echo 'deploy'
    }
    
}
