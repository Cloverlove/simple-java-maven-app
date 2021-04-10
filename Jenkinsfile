pipeline {
    agent { docker 'maven:3.3.3' } #代理，
    stages {  #阶段。
        stage('build') { #每一个阶段
            steps {   #每一个步骤
                sh 'mvn --version'
            }
        }
        stage('test') {
           steps {
              sh 'echo success'
           }
        }
    }
}
