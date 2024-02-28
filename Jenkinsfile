##Hello namaste jenkins
pipeline {
    agent any
    
    stages {
        stage('Hello') {
            steps {
                echo 'Hello, World!'
            }
        }
        
/*        stage('Unit Test') {
            steps {
                sh "npm i -g gulp"
                sh "npm install --silent --force"
                sh "npm run build"
                sh "npm run test:c"
            }
        }
        
        stage('Sonarqube') {
            environment {
                def scannerHome = tool 'SonarScannerOthers';
            }
            steps {
                withSonarQubeEnv('SonarQubeEE') {
                    sh "${scannerHome}/bin/sonar-scanner"
                }
            }
        }
        
        stage("Quality gate") {
            steps {
                waitForQualityGate abortPipeline: false
            }
        }*/
    }
}
